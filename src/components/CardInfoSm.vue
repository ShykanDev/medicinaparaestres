<template>
    <div class="p-5 font-poppins min-h-36">
        <div class="relative rounded-lg lg:flex lg:flex-row-reverse lg:items-center lg:text-2xl">
            <!-- Imagen superior -->
            <img v-if="showImgTop"
                 :class="{'-right-6': imgTopPosition === 'right', '-left-6': imgTopPosition === 'left'}"
                 class="absolute z-0 w-20 -top-10"
                 :src="imgTop"
                 alt="">

            <!-- Contenedor del texto y la imagen del centro -->
            <div class="p-1 border-l-4 lg:w-1/2 border-l-rose-300">
                <!-- Título arriba -->
                <h2 data-aos="fade-left" data-aos-delay="100" class="z-10 text-2xl font-semibold text-center text-rose-800 lg:text-5xl">{{ title }}</h2>
                <!-- Descripciones -->
                <p class="mt-3 leading-relaxed text-gray-600" v-html="highlightWord(description)"></p>
                <p class="mt-3 leading-relaxed text-gray-600" v-html="highlightWord(description2)"></p>
            </div>

            <!-- Imagen del centro en pantallas grandes al lado derecho -->
            <div class="flex items-center justify-center lg:w-1/2 lg:justify-start">
                <img v-if="showImgCenter"
                data-aos="fade-right"
                :class="imgCenterWidth" class="rounded-lg lg:w-[450px]" :src="imgCenter" alt="">
            </div>
        </div>
    </div>
</template>


<script lang="ts" setup>

const props = defineProps({
    title:{
        type: String,
        default: 'Lorem ipsum dolor.',
    },
    description:{
        type: String,
        default: ' Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi quibusdam doloremque saepe sit temporibus labore dolor cupiditate consequatur praesentium ut fugiat sequi, reprehenderit adipisci aut. Aliquam dolorem aspernatur dolores, similique non esse sed blanditiis eos inventore, voluptatum minima reiciendis quia rerum nostrum illum aut omnis impedit libero praesentium commodi magnam!',
    },
    description2:{
        type: String,
        default: '',
    },
    imgTop: {
        type: String,
        default: 'https://i.ibb.co/Q6z4d2p/pngwing-com.png',
    },
    imgTopPosition: {
        type: String,
        default: 'right',
    },
    showImgTop: {
        type: Boolean,
        default: true,
    },
    imgCenter: {
        type: String,
        default: 'https://images.pexels.com/photos/3233275/pexels-photo-3233275.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1',
    },
    imgCenterWidth: {
        type: String,
        default: 'w-20',
    },
    showImgCenter: {
        type: Boolean,
        default: true,
    },

})
const highlightWord = (text:string) => {
  return text.replace(/\b(estrés)\b/, '<span class="font-bold text-red-700">ESTRÉS</span>')
  .replace(/\b(cortisol)\b/, '<span class="font-bold text-red-700">CORTISOL</span>')
  .replace(/\b(calma)\b/, '<span class="font-bold text-red-700">CALMA</span>')
  .replace(/\b(bienestar)\b/, '<span class="font-bold text-red-700">BIENESTAR</span>')
  .replace(/\b(concentración)\b/, '<span class="font-bold text-red-700">CONCENTRACIÓN</span>')
  .replace(/\b(claridad)\b/, '<span class="font-bold text-red-700">CLARIDAD</span>')
  .replace(/\b(reducir)\b/, '<span class="font-bold text-red-700">REDUCIR</span>')
  .replace(/\b(mejorando)\b/, '<span class="font-bold text-red-700">MEJORANDO</span>')
  .replace(/\b(restaurar)\b/, '<span class="font-bold text-red-700">RESTAURAR</span>')
  .replace(/\b(protección)\b/, '<span class="font-bold text-red-700">PROTECCIÓN</span>')

}
</script>

<style scoped>

</style>
