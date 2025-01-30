<template>
	<div class="rive-container" :style="containerStyle">
		<canvas :id="canvasId" :width="canvasWidth" :height="canvasHeight" />
	</div>
</template>

<script setup>
import { onMounted, onUnmounted, ref, computed } from 'vue'
import { Rive, Layout, Fit, Alignment } from '@rive-app/canvas'

const props = defineProps({
	src: {
		type: String,
		required: true
	},
	width: {
		type: [String, Number],
		default: 400
	},
	height: {
		type: [String, Number],
		default: 300
	},
	fit: {
		type: String,
		default: 'contain'
	},
	alignment: {
		type: String,
		default: 'center'
	}
})

// Convert width/height to numbers and handle px values
const getNumericSize = (size) => {
	if (typeof size === 'number') return size
	return parseInt(size.replace('px', ''))
}

const containerStyle = computed(() => ({
	width: typeof props.width === 'number' ? `${props.width}px` : props.width,
	height: typeof props.height === 'number' ? `${props.height}px` : props.height
}))

// Calculate actual canvas dimensions
const dpr = window.devicePixelRatio || 1
const canvasWidth = computed(() => getNumericSize(props.width) * dpr)
const canvasHeight = computed(() => getNumericSize(props.height) * dpr)

const canvasId = `rive-canvas-${Math.random().toString(36).substr(2, 9)}`
let riveInstance = null

onMounted(async () => {
	const canvas = document.getElementById(canvasId)
	const ctx = canvas.getContext('2d')

	// Set canvas CSS size
	canvas.style.width = `${getNumericSize(props.width)}px`
	canvas.style.height = `${getNumericSize(props.height)}px`

	try {
		riveInstance = new Rive({
			canvas,
			src: props.src,
			layout: new Layout({
				fit: props.fit === 'contain' ? Fit.Contain : Fit.Cover,
				alignment: Alignment.Center,
			}),
			autoplay: true,
			stateMachines: ['State Machine 1'],
			useOffscreenRenderer: true,
			enableAudio: true,
		})

		// Log available state machines and artboards for debugging
		riveInstance.on('load', () => {
			console.log('Available state machines:', riveInstance)
		})

	} catch (error) {
		console.error('Error loading Rive animation:', error)
	}
})

onUnmounted(() => {
	if (riveInstance) {
		riveInstance.cleanup()
	}
})
</script>

<style scoped>
.rive-container {
	position: relative;
	background: transparent;
	border-radius: 8px;
	overflow: hidden;
}

canvas {
	display: block;
	width: 100%;
	height: 100%;
	touch-action: none; /* Prevents default touch behaviors */
}

.error-message {
	color: red;
	position: absolute;
	text-align: center;
	padding: 1rem;
}

.loading-message {
	position: absolute;
	text-align: center;
	padding: 1rem;
}
</style>
