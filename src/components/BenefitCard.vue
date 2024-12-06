<template>
    <div data-aos="flip-right" class="flex flex-col p-6 bg-white rounded-lg shadow-md w-96">
        <h2 class="text-2xl border-b-2 border-b-rose-600 text-rose-900">
            {{title}}
        </h2>
        <img alt="Imagen de Boswellia serrata, Curcuma longa y Pluchea lanceolata" class="object-cover w-full h-40 mt-4 rounded-t-lg" :src="image"/>
        <p class="mt-2 text-gray-600">
            {{ summary }}
        </p>
        <div class="mt-4">
            <p class="text-gray-600">{{ summary2 }}</p>
        </div>
    </div>
</template>

<script lang="ts" setup>
const props = defineProps({
  title: {
    type: String,
    default: 'Lorem ipsum dolor sit amet'
  },
  summary: {
    type: String,
    default: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id, voluptas. Facilis, temporibus obcaecati! Illo quaerat voluptate quasi tempora necessitatibus quae explicabo enim distinctio aperiam excepturi.'
  },
  summary2: {
    type: String,
    default: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos, iste.'
  },
  image: {
    type: String,
    default: 'https://storage.googleapis.com/a1aa/image/xHSvAScbY07yMttsu6fns5OrMg9fV1dVXfoUgAtW8f9hFiXPB.jpg'
  }
})
</script>

<style scoped>

</style>
