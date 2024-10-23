<script setup lang="ts">
import IconBootstrap from './icons/IconBootstrap.vue'
import IconVue from './icons/IconVue.vue'
</script>

<template>
  <footer class="bd-footer fixed-bottom py-4 py-md-5 mt-5 bg-body-tertiary">
    <div class="container py-4 py-md-5 px-4 px-md-3 text-body-secondary">
      <hr />
      <div class="row">
        <div class="col-lg-3 mb-3"></div>
        <div class="col-6 col-lg-2 offset-lg-1 mb-3">
          <h5>Build</h5>
          <ul class="list-unstyled">
            <li class="mb-2">
              <a
                class="d-inline-flex align-items-center mb-2 text-body-emphasis text-decoration-none"
                href="https://getbootstrap.com/"
                aria-label="Bootstrap"
              >
                <IconBootstrap />
                <span class="fs-5">Bootstrap</span>
              </a>
            </li>
            <li class="mb-2">
              <a
                class="d-inline-flex align-items-center mb-2 text-body-emphasis text-decoration-none"
                href="https://getbootstrap.com/"
                aria-label="Bootstrap"
              >
                <IconVue />
                <span class="fs-5">Vue.Js</span>
              </a>
            </li>
          </ul>
        </div>
        <div class="col-6 col-lg-2 mb-3">
          <h5>Link</h5>
          <ul class="list-unstyled">
            <li class="mb-2"><a href="">Github</a></li>
            <li class="mb-2"><a href="">LinkedIn</a></li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped></style>
