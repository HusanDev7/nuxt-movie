<script setup lang="ts">
import headerLayout from "@/layouts/headerLayout.vue";
import footerLayout from "@/layouts/footerLayout.vue";
</script>

<template>
    <headerLayout />
  <div class="wrapper container">
    <NuxtPage />
  </div>
    <footerLayout />
</template>

<style scoped>
.wrapper {
  margin-top: 200px;
}
</style>