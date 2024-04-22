<script setup>
import principal from '@/assets/principal.jpg'
</script>
<template>
  <AppHeader />
  <div class="container px-5 mx-auto block md:flex md:flex-wrap">
    <div class="w-full md:w-1/3 mt-4">
        <img :src="principal" class="w-full p-2 border-2 border-gray-300 rounded-md" />
    </div>
    <div class="w-full md:w-2/3">
        <div class="m-4">
            <h3 class="text-xl font-bold border-b-2 border-blue-300">प्राचार्य</h3>
            <h2 class="text-2xl mt-2">श्रीमती मंजु ढाका</h2>
            <p>M.Phil. (UGC), RSA (Rajasthan Sociological Association) - 2023</p>
            <p>अनुभव: 12+ वर्ष</p>
            <p>Aadhar No.: <strong>6486 0240 8618</strong></p>
            <p>PAN No:<strong> CBMPM3060P</strong></p>
            <p>Phone No:<strong> 8890489922</strong></p>
        </div>
        <div class="m-4">
            <h3 class="text-xl font-bold border-b-2 border-blue-300">स्टाफ</h3>
            <p>to be updated...</p>
        </div>
    </div>
  </div>
  <Footer />
</template>