<template>
	<div>
		<canvas ref="canvas" :width="width" :height="height"></canvas>
	</div>
</template>

<script setup>
import { onMounted, ref } from "vue";
import { Rive, Layout } from "@rive-app/canvas";

const props = defineProps({
	src: {
		type: String,
		required: true,
	},
	width: {
		type: String,
		default: "400",
	},
	height: {
		type: String,
		default: "400",
	},
	fit: {
		type: String,
		default: "contain",
	},
	alignment: {
		type: String,
		default: "center",
	},
});

const canvas = ref(null);

onMounted(() => {
	new Rive({
		canvas: canvas.value,
		src: props.src,
		layout: new Layout({
			fit: props.fit,
			alignment: props.alignment,
		}),
		autoplay: true,
	});
});
</script>

<style scoped>
.rive-container {
	position: relative;
	display: flex;
	justify-content: center;
	align-items: center;
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
