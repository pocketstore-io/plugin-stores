<template>
  <section class="bg-white px-3 py-3">
    <section class="grid grid-cols-6 gap-3">
      <div v-for="item in 3" class="col-span-6 md:col-span-2">
        <StoreCard />
      </div>
    </section>
  </section>
</template>

<script setup lang="ts">
import StoreCard from "./StoreCard.vue";
</script>