<script setup lang="ts">
import Resume from    './ExperienceView.vue'
import Contact from   '../views/ContactView.vue'
import About from   '../views/AboutView.vue'
import AboutMe from '../components/AboutMe.vue'

</script>

<template>
  <div class="row">
    <div class="col-12">
      <AboutMe></AboutMe>
    </div>
    <div class="col-3">
      <contact></contact>
      <About></About>
    </div>
    <div class="col-9">
      <Resume></Resume>
    </div>
  </div>
</template>

<style></style>
