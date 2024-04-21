<script setup>
import sports from '@/assets/sports.jpg'
import sports1 from '@/assets/sports1.jpg'
import m1 from '@/assets/media1.jpg'
import m2 from '@/assets/media2.jpg'
import m3 from '@/assets/media3.jpg'
import m4 from '@/assets/media4.jpg'
import m5 from '@/assets/media5.jpg'
</script>
<template>
  <AppHeader />
  <div class="container px-5 mx-auto block md:flex md:flex-wrap">
    <div class="w-full md:w-1/3 mt-6 pr-6">
        <img :src="sports1" class="block p-2 border-2 m-2 border-gray-300 shadow-2 rounded-md" />
        <img :src="sports" class="block p-2 border-2 m-2 border-gray-300 shadow-2 rounded-md" />
        
    </div>
    <div class="w-full md:w-2/3 mt-6 pl-6">
        <p class="text-lg">खेलों में यह क्षेत्र का एकमात्र महाविद्यालय है जिसने अंतर विश्वविद्यालय (राष्ट्रीय) स्तर पर प्रतिवर्ष भाग लिया है एवं सफलताएं प्राप्त की है।</p>
        <ul class="list-disc list-inside ml-5 text-lg">
            <li>2017-18: दो खिलाड़ियों, बलराम मेहता और रवींद्र कुमार, का अंतर विश्वविद्यालय फुटबॉल प्रतियोगिता मे चयन हुआ। </li>
            <li>20-08-2018: दो खिलाड़ियों का अंतर विश्वविद्यालय क्रॉस-कंट्री प्रतियोगिता मे चयन हुआ तथा 10 किलोमीटर मे महाविद्यालय की टीम विजेता रही।</li>
            <li>23-09-2018: अंतर विश्वविद्यालय क्रॉस-कंट्री प्रतियोगिता मे पुनः 3 खिलाड़ियों का चयन हुआ और महाविद्यालय की टीम विजेता रही। </li>
            <li>13-12-2021: अंतर विश्वविद्यालय क्रॉस-कंट्री प्रतियोगिता में महिला वर्ग के 10 किलोमीटर दौड़ में महाविद्यालय की टीम प्रथम स्थान विजेता रही।  </li>
            <li>27-12-2022: अंतर विश्वविद्यालय क्रॉस-कंट्री प्रतियोगिता मे पुनः एक खिलाड़ी का चयन हुआ। </li>
            <li>13-12-2023: पिस्टल 10mm प्रतियोगिता मे एक खिलाड़ी प्रथम विजेता रहा। </li>
            <li>30-12-2023: हाकी प्रतियोगिता मे महाविद्यालय के एक खिलाड़ी का चयन हुआ। </li>        
        </ul>
    </div>
  </div>
  <div class="m-4">
    <h3 class="text-xl font-bold border-b-2 border-blue-300">समाचार पत्रों से</h3>  
    <div class="grid grid-cols-3 gap-4">
    <!-- Your grid items go here -->
    <div class="bg-gray-200"><img :src="m1" /></div>
    <div class="bg-gray-300"><img :src="m2" /></div>
    <div class="bg-gray-300"><img :src="m3" /></div>
    <div class="bg-gray-300"><img :src="m4" /></div>
    <div class="bg-gray-300"><img :src="m5" /></div>
    <!-- ... more items ... -->
    </div>
</div>
  <Footer />
</template>