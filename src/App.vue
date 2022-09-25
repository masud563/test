<script setup>
import { RouterLink, RouterView } from 'vue-router'
import SideMenu from './components/SideMenu.vue'

</script>

<template>
  <div class="app">
    <SideMenu />
    <RouterView />
  </div>
</template>

<style scoped>

.app{
  display: flex;
}

</style>
