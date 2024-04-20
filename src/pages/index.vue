<script setup>
import AppHeader from '@/components/AppHeader.vue';
import slide1 from '@/assets/slide1.jpeg'

</script>

<template>
	<AppHeader />
	<div class="grid place-items-start min-h-[80vh]">
		<div>
			<p><img :src="slide1" /></p>
			<h2 class="py-5 text-3xl m-3">लक्ष्मी सह शिक्षा महाविद्यालय </h2>
		</div>
	</div>
</template>

<route lang="yaml">
name: home
</route>
