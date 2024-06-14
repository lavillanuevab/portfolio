<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import IconBootstrap from './components/icons/IconBootstrap.vue'
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <Navbar />
  <div class="container-xxl bd-gutter mt-3 my-md-4 bd-layout">
    <RouterView />
  </div>
  <Footer />
</template>

<style scoped></style>
