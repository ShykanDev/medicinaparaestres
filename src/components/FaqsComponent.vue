<template>
 <div data-aos="fade-up"
     class="p-6 border-2 shadow-xl border-rose-400 rounded-3xl bg-gradient-to-br from-purple-200 via-rose-200 to-rose-200">
  <div class="flex items-center mb-4">
    <i class="mr-4 text-2xl text-rose-600 fas fa-info"></i>
    <h2 class="text-3xl font-bold text-rose-700">{{ title }}</h2>
  </div>
  <div class="space-y-4">
    <p class="text-lg font-light text-gray-700">
      {{ answer }}
    </p>
  </div>
</div>

</template>

<script lang="ts" setup>
const props = defineProps({
  title: {
    type: String,
    default: 'Lorem ipsum',
  },
  answer: {
    type: String,
    default: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos, iste.',
    },

})
</script>

<style scoped>

</style>
