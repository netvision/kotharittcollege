<script setup>
import PDF from "pdf-vue3";
</script>
<template>
    <AppHeader />
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 mb-12">
        <h2 class="text-2xl p-2 px-8">Principal:
		<span class="p-2 px-8 border-b-2">Dr. Narendra</span></h2>
		<PDF src="./staff1.pdf" />

    </div>
    <Footer />
</template>
