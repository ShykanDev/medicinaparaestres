
<template>
  <div
    class="p-6 transition-shadow bg-white rounded-lg shadow-lg hover:shadow-xl max-w-96">
    <!-- Imagen -->
    <img
      :src="image"
      :alt="altText"
      class="object-cover w-full h-40 rounded-t-lg"
    />

    <!-- Título -->
    <h3
      class="mt-4 text-xl font-bold text-center text-rose-700">
      {{ title }}
    </h3>

    <!-- Descripción -->
    <p class="mt-2 text-center text-gray-600" v-html="highlightWord(description)">
    </p>

    <!-- Lista de puntos -->
    <ul class="mt-4 space-y-1">
      <li v-for="(point, index) in points" :key="index" class="flex items-center text-rose-950">
        <!-- <i class="mr-2 text-green-500 fas fa-check"></i> -->
        {{ point }}
      </li>
    </ul>

    <!-- Resumen adicional -->
    <p class="mt-4 text-sm text-gray-500">
      {{ summary }}
    </p>
  </div>



</template>

<script setup lang="ts">
import { defineProps } from 'vue';

// Props para el contenido dinámico
defineProps({
  image: {
    type: String,
    default: "https://storage.googleapis.com/a1aa/image/7fb63a85-3ce6-4a2e-bb7f-4a7523c7acd6.jpeg",
  },
  altText: {
    type: String,
    default: "Imagen relacionada",
  },
  title: {
    type: String,
    default: "Título de ejemplo",
  },
  description: {
    type: String,
    default: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla facilisi.",
  },
  points: {
    type: Array,
    default: () => [
      "Punto destacado 1",
      "Punto destacado 2",
      "Punto destacado 3",
    ],
  },
  summary: {
    type: String,
    default: "Este es un resumen adicional para completar la información de la card.",
  },
});

const highlightWord = (text:string) => {
  return text.replace(/\b(estrés)\b/, '<span class="font-bold text-red-700">ESTRÉS</span>')
  .replace(/\b(cortisol)\b/, '<span class="font-bold text-red-700">CORTISOL</span>')
  .replace(/\b(calma)\b/, '<span class="font-bold text-red-700">CALMA</span>')
  .replace(/\b(bienestar)\b/, '<span class="font-bold text-red-700">BIENESTAR</span>')
  .replace(/\b(concentración)\b/, '<span class="font-bold text-red-700">CONCENTRACIÓN</span>')
  .replace(/\b(claridad)\b/, '<span class="font-bold text-red-700">CLARIDAD</span>')
  .replace(/\b(reducir)\b/, '<span class="font-bold text-red-700">REDUCIR</span>')
  .replace(/\b(mejorando)\b/, '<span class="font-bold text-red-700">MEJORANDO</span>')

}
</script>


<style scoped>

</style>
