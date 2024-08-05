<script setup lang="ts">
import headerLayout from "@/layouts/headerLayout.vue";
import footerLayout from "@/layouts/footerLayout.vue";
</script>

<template>
  <div class="wrapper">
    <headerLayout />
    <NuxtPage />
    <footerLayout />
  </div>
</template>