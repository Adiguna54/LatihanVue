<script setup>
import LogicFirst from "@/components/logic/LogicFirst.vue";
</script>

<template>
  <div class="mb-8 text-xl text-center capitalize about">
    <h1>This is an <span class="font-bold underline">logic</span> page</h1>
  </div>

  <div>
    <LogicFirst />
  </div>
</template>

<style scoped>
.button1 {
  @apply font-bold px-10 py-5 bg-blue-500;
}

.button2 {
  @apply font-bold px-10 py-5 bg-red-500 text-white;
}
</style>
