<script setup>
import TheHeader from './components/TheHeader.vue'
import CardItems from './components/CardItems.vue'
</script>

<template>
  <div class="bg-white w-4/5 m-auto rounded-xl shadow-xl mt-14">
    <TheHeader />
    <div class="p-10">
      <h2 class="text-3xl font-bold mb-8">Все кроссовки</h2>
      <CardItems />
    </div>
  </div>
</template>
