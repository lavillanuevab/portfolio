<script setup lang="ts">
import {computed} from 'vue';

const props = defineProps<{
  card_header: string;
  card_title: string;
  card_text: string;
  card_href?: string;
  card_href_text?: string;
}>();

// Computed property para transformar los puntos en saltos de línea
const formattedText = computed(() => {
  return props.card_text.replace(/• /g, '<br>• ');
});


</script>

<template>
  <div class="card">
    <div class="card-header small-title">
      {{ card_header }}
      <a v-if="card_href" :href="card_href" class="btn btn-primary">{{ card_href_text }}</a>
    </div>
    <div class="card-body">
      <h5 class="card-title">{{ card_title }}</h5>

      <!-- Usar v-html para renderizar el texto con <br> -->        
      <p v-html="formattedText"></p>
    </div>
  </div>
  <br>


</template>
<style scoped>
.small-title {
  font-size: 0.9rem; /* Ajusta el tamaño a tu preferencia */
}
</style>
