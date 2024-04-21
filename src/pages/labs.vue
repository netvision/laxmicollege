<script setup>
import library from '@/assets/library.jpg'
import lab1 from '@/assets/lab1.jpg'
import lab2 from '@/assets/lab2.jpg'
import lab3 from '@/assets/lab3.jpg'
import lab4 from '@/assets/lab4.jpg'
import lab5 from '@/assets/lab5.jpg'

</script>
<template>
  <AppHeader />
  <div class="m-4 mb-8">
    <h3 class="text-xl font-bold border-b-2 border-blue-300">प्रयोगशालाएं एवं लाईब्रेरी</h3>
    <div class="text-lg py-3">
            <p>संस्था मे विश्वविद्यालय द्वारा निर्धारित मानदंडों के अनुरूप एक दस हजार से अधिक पुस्तकों और पत्रिकाओं से परिपूर्ण लाइब्रेरी एवं सभी आवश्यक उपकरणों एवं साजो सामान से सुसज्जित निम्न प्रयोगशालाएं संचालित है :</p>
            <ul class=" list-disc list-inside pl-5">
               <li>प्राणिशास्त्र</li>
               <li>वनस्पति शास्त्र</li>
               <li>रसायन शास्त्र</li>
               <li>गणित</li>
               <li>भौतिक शास्त्र</li>
               <li>भूगोल</li> 
               <li>Computer</li> 
            </ul>
        </div>
    <div class="grid grid-cols-3 gap-4">
        <div class="text-lg py-3">
            <img :src="library" />
        </div>
        <div class="text-lg py-3">
            <img :src="lab1" />
        </div>
        <div class="text-lg py-3">
            <img :src="lab2" />
        </div>
        <div class="text-lg py-3">
            <img :src="lab3" />
        </div>
        <div class="text-lg py-3">
            <img :src="lab4" />
        </div>
        <div class="text-lg py-3">
            <img :src="lab5" />
        </div>
    </div>
    </div>
  <Footer />
</template>