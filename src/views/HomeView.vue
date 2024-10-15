<script setup>
 import Hero from '@/components/HeroSection.vue';
 import HomeCards from '@/components/HomeCards.vue';
 import JobListings from '@/components/JobListings.vue';
</script>

<template>
  <Hero title="Title from App.vue" subtitle="From app.vue again"/>
  <HomeCards/>
  <JobListings :limit="3" :showButton="true"/>
</template>