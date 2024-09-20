<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <header>
    <!-- <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" /> -->

    <div class="mb-8">
      <!-- <HelloWorld msg="Nice You Did It !!!" /> -->
      <nav class="nav">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/logic">Logic</RouterLink>
      </nav>
    </div>
  </header>
  <div class="">
    <RouterView />
  </div>
</template>

<style scoped>
.nav {
  @apply flex rounded-md border-2 border-black bg-[#FFC94A] text-black font-bold text-3xl justify-between mt-4 mx-16 px-8 py-2;
}
</style>
