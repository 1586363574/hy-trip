<template>
  <div class="app">
    <router-view></router-view>
    <tab-bar />
  </div>
</template>
<script setup>
import tabBar from "@/components/tab_bar/tab-bar.vue";
</script>
<style scoped></style>