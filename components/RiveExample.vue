<template>
	<div class="rive-container" :style="{ width, height }">
		<canvas :id="canvasId" />
	</div>
</template>

<script setup>
import { onMounted, onUnmounted } from 'vue'
import { Rive, Layout, Fit, Alignment } from '@rive-app/canvas'

const props = defineProps({
	src: {
		type: String,
		required: true
	},
	width: {
		type: String,
		default: '400px'
	},
	height: {
		type: String,
		default: '300px'
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

const canvasId = `rive-canvas-${Math.random().toString(36).substr(2, 9)}`
let riveInstance = null

onMounted(async () => {
	const canvas = document.getElementById(canvasId)

	riveInstance = new Rive({
		canvas,
		src: props.src,
		layout: new Layout({
			fit: props.fit === 'contain' ? Fit.Contain : Fit.Cover,
			alignment: Alignment.Center,
		}),
		autoplay: true,
	})
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
	background: #1a1a1a;
	border-radius: 8px;
	overflow: hidden;
}

canvas {
	width: 100%;
	height: 100%;
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
