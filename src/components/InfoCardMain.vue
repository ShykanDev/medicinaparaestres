<template>
  <div
    class="mx-auto overflow-hidden transition-transform border shadow-lg max-w-96 bg-gradient-to-b from-orange-50 to-white rounded-xl hover:scale-105"
  >
    <!-- Imagen -->
    <div class="relative w-full h-48 overflow-hidden rounded-t-xl">
      <img
        :src="image"
        alt="Card image"
        class="object-cover w-full h-full transition-opacity hover:opacity-90"
      />
      <div
        class="absolute inset-0 opacity-50 bg-gradient-to-t from-black via-transparent to-transparent"></div>
    </div>

    <!-- Contenido -->
    <div class="p-5">
      <!-- Título -->
      <h2
        class="mb-3 text-lg font-bold tracking-wide text-center text-gray-800 font-poppins">
        {{ title }}
      </h2>

      <!-- Resumen -->
      <p class="text-sm leading-relaxed text-justify text-gray-600">
        {{ summary }}
      </p>


    </div>
  </div>
</template>

<script setup lang="ts">
import { defineProps } from 'vue';

// Definimos las props con valores predeterminados
defineProps({
  title: {
    type: String,
    default: 'Título de ejemplo',
  },
  summary: {
    type: String,
    default: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla eget massa nec nunc pretium consequat.',
  },
  image: {
    type: String,
    default: 'https://storage.googleapis.com/a1aa/image/MWJSpm8Ynar9AF9kA7luRMNBDgJW7uTpccNt2dHQLEG1oU9E.jpg',
  },
});
</script>
