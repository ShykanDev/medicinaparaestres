<template>
    <div class="">
        <MainLayout>
            <template #main>
                <div class="flex justify-center gap-2 py-3 overflow-hidden text-4xl font-semibold text-white bg-rose-600 font-poppins">
                <p class="animate-fade-left">Ingredientes de</p>
                <p class="animate-fade-left animate-delay-150">Alak</p>
                <p class="animate-fade-left animate-delay-300">Rasayan</p>
              </div>
                <section class="flex flex-wrap justify-around">
                    <IngredientsCard v-for="ingredient in ingredients" :key="ingredient.mainTitle"
                        :mainTitle="ingredient.mainTitle" :smallIntro="ingredient.smallIntro"
                        :description="ingredient.description" :imgSrc="ingredient.imgSrc"
                        :infoArr="ingredient.infoArr" />
                </section>
            </template>
        </MainLayout>
    </div>
</template>

<script lang="ts" setup>
import IngredientsCard from '@/components/IngredientsCard.vue';
import MainLayout from '@/layouts/MainLayout.vue';
const ingredients = [
  {
    "mainTitle": "Ashwagandha (Withania somnifera)",
    "smallIntro": "Conocida por sus propiedades adaptógenas, la Ashwagandha ayuda a reducir el estrés y aumentar la resiliencia emocional.",
    "description": "La Ashwagandha es una hierba adaptógena que regula los niveles de cortisol, la hormona del estrés, y ayuda a equilibrar el sistema nervioso. Su consumo regular puede reducir la ansiedad, promover la relajación y mejorar la resistencia al estrés. Además, mejora la calidad del sueño, ayudando a restablecer el bienestar emocional y físico.",
    "imgSrc": "https://storage.googleapis.com/a1aa/image/cf8c9f1c-a020-4ddd-bb6f-e5f6eb34fc30.jpeg",
    "infoArr": [
      { "id": 2, "property": "Propiedades", "description": "Adaptógena, reguladora de cortisol, mejora el sueño" },
      { "id": 3, "property": "Beneficios", "description": "Reduce el estrés y la ansiedad, mejora la resistencia emocional, promueve la relajación." },
      { "id": 4, "property": "Usos comunes", "description": "Se utiliza para reducir los efectos del estrés crónico y la fatiga mental." },
      { "id": 5, "property": "Mecanismo de acción", "description": "Modula los niveles de cortisol, ayudando a reducir el estrés y promoviendo un equilibrio emocional." }
    ]
  },
  {
    "mainTitle": "Amla (Phyllanthus emblica)",
    "smallIntro": "El Amla es una fruta rica en vitamina C que combate el estrés oxidativo y fortalece el sistema nervioso.",
    "description": "El Amla, también conocido como grosella india, es un potente antioxidante que ayuda a reducir el estrés oxidativo causado por los radicales libres. Además, actúa como un tónico para el sistema nervioso, ayudando a calmar la mente y reducir la ansiedad. Su alto contenido en vitamina C también favorece la producción de neurotransmisores, promoviendo la relajación mental y la claridad emocional.",
    "imgSrc": "https://storage.googleapis.com/a1aa/image/39926d27-010c-4e4b-9ead-8e68aceeeed1.jpeg",
    "infoArr": [
      { "id": 2, "property": "Propiedades", "description": "Antioxidante, tónico nervioso, rico en vitamina C" },
      { "id": 3, "property": "Beneficios", "description": "Reduce el estrés oxidativo, mejora la función cerebral y combate la ansiedad." },
      { "id": 4, "property": "Usos comunes", "description": "Usado para reducir el estrés, mejorar la memoria y la claridad mental." },
      { "id": 5, "property": "Mecanismo de acción", "description": "Ayuda a calmar el sistema nervioso y a proteger las células del daño causado por el estrés." }
    ]
  },
  {
    "mainTitle": "Prickly Pear (Opuntia ficus-indica)",
    "smallIntro": "El nopal, o Prickly Pear, es un superalimento que ayuda a equilibrar los niveles de estrés y promueve la salud emocional.",
    "description": "El Prickly Pear, o nopal, es conocido por sus propiedades antioxidantes y antiinflamatorias. Además, es rico en fibra y minerales, lo que ayuda a equilibrar el azúcar en sangre y reducir los picos de estrés relacionados con la ansiedad y la fatiga. Su consumo regular puede mejorar el bienestar general, ayudando a combatir el estrés y promoviendo una sensación de calma y estabilidad emocional.",
    "imgSrc": "https://storage.googleapis.com/a1aa/image/bb82da2f-bfcb-4281-ad43-9428fd928df9.jpeg",
    "infoArr": [
      { "id": 2, "property": "Propiedades", "description": "Antioxidante, antiinflamatorio, ayuda a regular el azúcar en sangre" },
      { "id": 3, "property": "Beneficios", "description": "Reduce la ansiedad y el estrés, mejora el equilibrio emocional y promueve la relajación." },
      { "id": 4, "property": "Usos comunes", "description": "Se utiliza para equilibrar el sistema nervioso y reducir los efectos del estrés en el cuerpo." },
      { "id": 5, "property": "Mecanismo de acción", "description": "Ayuda a regular el azúcar en sangre y a calmar el cuerpo, reduciendo los efectos negativos del estrés." }
    ]
  }
];



</script>

<style scoped></style>
