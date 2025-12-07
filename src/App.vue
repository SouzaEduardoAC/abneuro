<script setup lang="ts">
import SEO from './components/SEO.vue'
import TheHeader from './components/TheHeader.vue'
import TheHero from './components/TheHero.vue'
import TheAbout from './components/TheAbout.vue'
// import TheServices from './components/TheServices.vue'
import TheMedia from './components/TheMedia.vue'
import TheLocation from './components/TheLocation.vue'
import TheFooter from './components/TheFooter.vue'
</script>

<template>
  <SEO />
  <TheHeader />
  <main>
    <TheHero />
    <TheAbout />
    <!-- <TheServices /> -->
    <TheMedia />
    <TheLocation />
  </main>
  <TheFooter />
</template>

<style>
/* Global styles are in assets/main.css */
</style>
