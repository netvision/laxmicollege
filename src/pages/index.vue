<script setup>
import AppHeader from '@/components/AppHeader.vue';
import secretary from '@/assets/secretary-laxmicollege.jpg'
import slide2 from '@/assets/slide2.jpeg'

</script>

<template>
	<AppHeader />
	<img :src="slide2" />
	<div class="container px-5 mx-auto flex flex-wrap mb-6">
		<div
			class="h-full w-1/3 rounded-lg bg-white shadow-secondary-1 dark:bg-surface-dark p-6">
			<a href="#!">
				<img
				class="rounded-t-lg w-full object-cover"
				:src="secretary"
				alt="Shri Girdharilal Phogat" />
			</a>
			<div class="p-6 text-surface dark:text-white">
				<h5 class="mb-2 text-xl font-medium leading-tight">श्री गिरधारीलाल फोगाट</h5>
				<p class="mb-4 text-base">
				<strong>प्रबंधक, लक्ष्मी सह शिक्षा पीजी महाविद्यालय</strong>
				</p>
			</div>
		</div>
		<div class="text-justify text-lg p-5 w-2/3">
			<h2 class="py-5 text-3xl m-3 text-center">लक्ष्मी सह शिक्षा पीजी महाविद्यालय </h2>
			<p>पंडित दीनदयाल उपाध्याय शेखावाटी विश्वविद्यालय, सीकर (राजस्थान) से संबद्ध यह महाविद्यालय इस्माइलपुर (पिचानवां खुर्द), लालचौक में स्थित है।</p>
			<p> झुनझुनू ज़िले के इस श्रेष्ठ महाविद्यालय में कला एवं विज्ञान संकाय में निम्नलिखित विषय उपलब्ध है:</p>
			<ul class="list-disc mb-2 pl-6">
				<li class="py-3"><strong>स्नातक (UG):</strong>
					<ul>
						<li><strong>कला संकाय: </strong>अंग्रेज़ी साहित्य, हिन्दी साहित्य, भूगोल, राजनीति विज्ञान, इतिहास, एवं अर्थशास्त्र </li>
						<li><strong>विज्ञान संकाय: </strong>प्राणिशास्त्र, वनस्पति शास्त्र, रसायन शास्त्र, गणित एवं भौतिक शास्त्र </li>
					</ul>
				</li>
				<li><strong>स्नातकोत्तर (PG):</strong>
					<ul>
						<li><strong>कला संकाय: </strong>राजनीति विज्ञान, भूगोल एवं इतिहास </li>
						<li><strong>विज्ञान संकाय: </strong>वनस्पति शास्त्र एवं गणित</li>
					</ul>
				</li>
			</ul>
			<p>वर्तमान में महाविद्यालय में लगभग 600 छात्र-छात्राएं नियमित रूप से अध्ययनरत हैं। </p>
			<p>खेलों में यह क्षेत्र का एकमात्र महाविद्यालय है जिसने अंतर विश्वविद्यालय (राष्ट्रीय) स्तर पर प्रतिवर्ष भाग लिया है एवं सफलता प्राप्त की है।</p>
			<p>सरकार द्वारा दी जाने वाली छात्रवृत्तियाँ सभी योग्य छात्र छात्राओं को दिलाने में पूर्ण सहयोग दिया जाता है तथा इसके साथ ही ग़रीब एवं विकलांग छात्र छात्राओं को महाविद्यालय द्वारा भी विशेष आर्थिक सहयोग दिया जाता है। संस्था का परीक्षा परिणाम उत्तम रहता है।</p>
		</div>
	</div>
	<Footer />
</template>
<style scoped>
p {
	@apply py-2 first-line:pl-3
}
</style>

<route lang="yaml">
name: home
</route>
