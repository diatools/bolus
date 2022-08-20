<script setup lang="ts">
import { RouterView } from "vue-router";
import HeaderBar from "./components/HeaderBar.vue";
import FooterBar from "./components/FooterBar.vue";
</script>

<template>
  <HeaderBar />
  <main>
    <RouterView />
  </main>
  <FooterBar />
</template>

<style scoped lang="less">
main {
  flex: 1;
  background: white;
  padding: var(--vpadding) var(--left);
}
</style>
