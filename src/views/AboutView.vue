
<script setup lang="ts">
import kotakkuning from '@/components/kotakkuning.vue'
import kotakmerah from '@/components/kotakmerah.vue'
import kotakbiru from '@/components/kotakbiru.vue'
</script>

<template>
  <div class="about">
    <kotakkuning/>
    <kotakmerah/>
    <kotakbiru/>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
