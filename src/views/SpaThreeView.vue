<template>
  <div class="">
    <MainLayout>
      <template #main>
        <div class="flex justify-center gap-2 py-3 overflow-hidden text-4xl font-semibold text-white bg-rose-600 font-poppins">
  <p class="animate-fade-left">Preguntas</p>
  <p class="animate-fade-left animate-delay-150">Frecuentes</p>
  <p class="animate-fade-left animate-delay-300">sobre Alak</p>
  <p class="animate-fade-left animate-delay-500">Rasayan</p>
</div>

        <div class="container p-6 mx-auto">
          <div class="grid grid-cols-1 gap-6 md:grid-cols-2 lg:grid-cols-3 font-poppins">

            <FaqsComponent v-for="faq in faqs" :key="faq.title" :title="faq.title" :answer="faq.answer"/>

          </div>
        </div>
      </template>
    </MainLayout>
  </div>
</template>

<script lang="ts" setup>

import FaqsComponent from '@/components/FaqsComponent.vue';
import MainLayout from '@/layouts/MainLayout.vue';

const faqs = [
  {
    title: '¿Qué es Alak Rasayan y cómo ayuda al estrés?',
    answer: 'Alak Rasayan es un suplemento natural compuesto por un 30% de Ashwagandha, un 30% de Amla y un 30% de Prickly Pear. Está formulado para reducir el estrés y promover el equilibrio emocional, ayudando a tu cuerpo a adaptarse mejor a las situaciones estresantes.'
  },
  {
    title: '¿Cómo ayuda la Ashwagandha en Alak Rasayan a reducir el estrés?',
    answer: 'La Ashwagandha es conocida por sus propiedades adaptogénicas, que ayudan al cuerpo a lidiar con el estrés físico y emocional, promoviendo una sensación de calma y reduciendo la ansiedad.'
  },
  {
    title: '¿Dónde puedo comprarlo?',
    answer: 'Sólo contactenos, estraemos encantados de ayudarle con su compra, puede hacerlo mediante cualquiera de nuestros medios de contacto.'
  },
  {
    title: '¿El Amla tiene beneficios para el estrés?',
    answer: 'Sí, el Amla, además de ser un potente antioxidante, también ayuda a equilibrar el sistema nervioso. Su riqueza en vitamina C y otros nutrientes contribuye a la reducción de los efectos del estrés en el cuerpo.'
  },
  {
    title: '¿De qué manera el Prickly Pear ayuda con el estrés?',
    answer: 'El Prickly Pear tiene propiedades antiinflamatorias y antioxidantes, que no solo mejoran la salud general, sino que también ayudan a reducir el estrés oxidativo y las respuestas inflamatorias asociadas con el estrés crónico.'
  },
  {
    title: '¿Cuánto tiempo tarda Alak Rasayan en reducir el estrés?',
    answer: 'Los efectos de Alak Rasayan pueden comenzar a notarse en tan solo una semana de uso continuo. Sin embargo, para resultados más notables en la reducción del estrés, se recomienda un uso constante durante al menos 2-4 semanas.'
  },
  {
    title: '¿Puedo tomar Alak Rasayan si estoy muy estresado o ansioso?',
    answer: 'Sí, Alak Rasayan es una excelente opción para quienes buscan reducir el estrés y la ansiedad. Sus ingredientes naturales trabajan en conjunto para mejorar la respuesta del cuerpo al estrés y promover el bienestar emocional.'
  },
  {
    title: '¿Es seguro usar Alak Rasayan a largo plazo para el estrés?',
    answer: 'Alak Rasayan es seguro para su uso a largo plazo, gracias a sus ingredientes naturales y adaptogénicos. Sin embargo, si tienes alguna preocupación de salud o estás tomando otros medicamentos, siempre es recomendable consultar a un médico antes de su uso prolongado.'
  },
  {
  title: '¿Alak Rasayan ayuda a mejorar la calidad del sueño en momentos de estrés?',
  answer: 'Sí, Alak Rasayan puede ayudar a mejorar la calidad del sueño al reducir el estrés y la ansiedad. La Ashwagandha, en particular, tiene propiedades que promueven la relajación y el descanso, ayudando a conciliar el sueño más fácilmente.'
},
{
  title: '¿Puede Alak Rasayan ayudar a lidiar con el estrés relacionado con el trabajo?',
  answer: 'Definitivamente. Alak Rasayan es una excelente opción para combatir el estrés relacionado con el trabajo. Gracias a sus ingredientes como la Ashwagandha, que ayuda a regular el sistema nervioso y la respuesta al estrés, este suplemento puede mejorar tu resistencia al estrés laboral y ayudarte a mantener la calma y concentración.'
}

];

</script>

<style scoped></style>
