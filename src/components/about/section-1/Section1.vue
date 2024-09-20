<script setup></script>
<template>
  <!-- Top -->
  <div class="em-section-1">
    <div class="flex flex-row gap-32 px-[296px] mb-36">
      <!-- left -->
      <div class="h-[596px] w-full">
        <img src="/src/images/front.png" alt="about-1" class="object-cover h-full" />
      </div>

      <!-- Right -->
      <div class="flex flex-col">
        <h2 class="em-text-1 pb-[40px]">About Us</h2>
        <h1 class="em-title-1 pb-[62px]">We always make The Best</h1>
        <p class="em-text-1 pb-[61px]">
          Bali Team Construction is a company for the construction and decoration of
          premises. We carry out projects on time, within budget and with an exceptional
          level of quality
        </p>

        <!-- Button -->
        <div>
          <button
            type="button"
            class="bg-[#FFC94A] em-text-1 rounded-md border-2 border-black px-[66px] py-[18px]"
          >
            <a href="#" target="_blank" rel="noopener noreferrer">Contact Us</a>
          </button>
        </div>
      </div>
    </div>

    <!-- Bottom -->
    <div class="px-[265px] flex flex-row gap-32 justify-between">
      <!-- Left -->
      <div class="flex flex-col gap-7">
        <h1 class="em-title-2">Our Experience</h1>
        <p class="em-text-1 max-w-[665px]">
          our seasoned team of architects, engineers, and skilled tradespeople bring a
          wealth of experience to every project. We understand that each construction
          endeavor is unique, demanding a blend of innovation, precision, and expert
          execution.
        </p>
      </div>

      <!-- Right -->
      <div class="grid grid-cols-2 gap-40">
        <div>
          <h1 class="pb-8 em-title-3">20+</h1>
          <span class="em-text-2">Year Of experience</span>
        </div>

        <div>
          <h1 class="pb-8 em-title-3">30+</h1>
          <span class="em-text-2">Project Done</span>
        </div>

        <div>
          <h1 class="pb-8 em-title-3">10+</h1>
          <span class="em-text-2">On-going Project</span>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.em-text-1 {
  @apply text-xl/[40px] font-light;
}

.em-text-2 {
  @apply text-xl/[40px];
}

.em-title-1 {
  @apply text-[64px]/[64px] capitalize;
}

.em-title-2 {
  @apply text-[60px]/[40px] font-light;
}

.em-title-3 {
  @apply font-medium text-8xl/[40px];
}

.em-section-1 {
  @apply h-full w-full mb-16;
}
</style>
