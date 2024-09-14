<script setup>
import Section1 from "@/components/about/section-1/Section1.vue";
import Section2 from "@/components/about/section-2/Section2.vue";
</script>
<template>
  <div class="about capitalize text-xl text-center mb-8">
    <h1>This is an about page</h1>
  </div>

  <div>
    <Section1 />
    <Section2 />
  </div>
</template>

<style>
/* @media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
} */
</style>
