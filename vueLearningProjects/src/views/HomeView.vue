<script setup>
import HomeViewComponent from '@/components/HomeViewComponent.vue';

</script>

<template>
  <main>
    <HomeViewComponent :default-value="123">

      <button>button from out side</button>

    </HomeViewComponent>
  </main>
</template>
