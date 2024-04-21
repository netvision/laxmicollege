<script setup>
import { GoogleMap, Marker } from 'vue3-google-map'
import geotag from '@/assets/geotagphoto.jpg'
const mapApi = ref(import.meta.env.VITE_MAPKEY)
const center = { lat: 28.199406, lng: 75.705798 }
</script>

<template>
    <AppHeader />
    <GoogleMap
  :api-key="mapApi"
  style="width: 100%; height: 500px"
  :center="center"
  :zoom="15"
  >
    <Marker :options="{ position: center, label: 'L', title: 'Laxmi Co-education PG College' }" />
  </GoogleMap>
  <div class="block md:flex md:flex-row p-6 mb-12">
    <div class="w-full md:w-1/3">
        <img :src="geotag" class="w-full p-2 border border-gray-800 border-2" />
    </div>
    <div class="w-full md:w-2/3 p-16">
        <h2 class="py-5 text-2xl mx-5 text-left">लक्ष्मी सह शिक्षा महाविद्यालय </h2>
        <p class="pl-5 text-lg">इस्माइलपुर (पिचानवां खुर्द), लालचौक</p>
        <p class="pl-5 text-lg">सिंघाना चिड़ावा स्टेट हाइवै-13 </p>
        <p class="pl-5 text-lg">फोन नं : 9001992249 </p>
    </div>
  </div>
  <Footer />
</template>