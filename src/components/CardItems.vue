<script setup>
import SneakerCard from './SneakerCard.vue'
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <SneakerCard
      title="Мужские Кроссовки Nike Blazer Mid Suede"
      image-url="/sneakers/sneakers-1.jpg"
      :price="8000"
      :is-added="true"
      :is-favorite="true"
    />
    <SneakerCard />
    <SneakerCard />
    <SneakerCard />
    <SneakerCard />
  </div>
</template>
