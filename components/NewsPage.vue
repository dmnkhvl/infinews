<template>
  <div class="container">
    <div class="flex justify-between items-center mb-4 text-white text-lg">
      <h1 class="uppercase">{{ heading }}</h1>
      <p>ST</p>
    </div>
    <news-article />
  </div>
</template>
<script setup>
const props = defineProps({
  heading: String,
});
</script>
