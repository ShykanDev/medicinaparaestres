<template>
    <div class="">
      <header class="sticky top-0 z-50 w-full shadow-lg bg-gradient-to-br from-rose-600 via-rose-500 to-slate-900">
  <!-- Barra superior -->
  <section class="flex items-center justify-between px-4 py-2 text-sm text-white">
    <img class="hidden h-8 md:block" src="../assets/ssl-certificate.png" alt="Certificado SSL">
   <div class="hidden text-xl md:flex"><span><span class="text-white animate-fade-down">medicina</span><span class="text-yellow-200 animate-fade-down">para</span><span class=" animate-fade-down">estres</span><span class="text-yellow-200 animate-fade-down">.com </span></span></div>
    <img class="h-8" src="https://medicinaparaansiedad.com/img/logo.png" alt="Logo">
    <div class="flex flex-wrap items-center justify-center gap-4 font-semibold md:justify-start font-poppins">
    <a href="tel:+525563950178" class="flex items-center gap-2 hover:underline">
      <i class="fas fa-phone"></i>
      <span>+52 55 6395 0178</span>
    </a>
    <a href="tel:+525563950179" class="flex items-center gap-2 hover:underline">
      <i class="fas fa-phone"></i>
      <span>+52 55 6395 0179</span>
    </a>
    <a href="mailto:informes@prasadam.mx" class="flex items-center gap-2 hover:underline">
      <i class="fas fa-envelope"></i>
      <span>informes@prasadam.mx</span>
    </a>
    <a href="https://wa.me/525562516687" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 hover:underline">
      <i class="fab fa-whatsapp"></i>
      <span>+52 5562516687</span>
    </a>
  </div>
  </section>

  <!-- Navegación principal -->
  <nav class="flex justify-center bg-white shadow-md">
  <ul class="flex px-6 py-4 space-x-6 text-base font-medium text-gray-700">
    <li>
      <RouterLink
        :class="route.name === 'home' ? 'text-rose-500 border-b-2 border-rose-500' : 'animate-fade-up'"
        :to="{ name: 'home' }"
      >
        <i class="mr-2 fas fa-home"></i> Inicio
      </RouterLink>
    </li>
    <li>
      <RouterLink
        :class="route.name === 'spaOne' ? 'text-rose-500 border-b-2 border-rose-500' : 'hover:px-2 py-1 rounded-lg animate-fade-up'"
        :to="{ name: 'spaOne' }"
      >
        <i class="mr-2 fas fa-heartbeat"></i> Beneficios
      </RouterLink>
    </li>
    <li>
      <RouterLink
        :class="route.name === 'spaTwo' ? 'text-rose-500 border-b-2 border-rose-500' : 'hover:px-2 py-1 rounded-lg animate-fade-up'"
        :to="{ name: 'spaTwo' }"
      >
        <i class="mr-2 fas fa-capsules"></i> Ingredientes
      </RouterLink>
    </li>
    <li>
      <RouterLink
        :class="route.name === 'spaThree' ? 'text-rose-500 border-b-2 border-rose-500' : 'px-2 py-1 rounded-lg animate-fade-up'"
        :to="{ name: 'spaThree' }"
      >
        <i class="mr-2 fas fa-question-circle"></i> Preguntas
      </RouterLink>
    </li>
    <a class="hidden md:block" href="https://www.prasadam.mx/" target="_blank" rel="noopener noreferrer">
      <i class="mr-2 fas fa-gift"></i> Prasadam
    </a>
  </ul>
</nav>

</header>

        <main class="overflow-hidden">
            <slot name="main">

            </slot>
        </main>
        <footer class="relative w-full p-6 text-white bg-rose-800 font-poppins">
        <!-- Sección Título -->
        <div class="mb-6 text-center">
            <h2 class="text-3xl font-bold lg:text-5xl">Contacto</h2>
        </div>

        <!-- Imagen de seguridad SSL -->
        <div class="absolute top-4 right-4">
            <img class="w-12 lg:w-16" src="https://shykandev.github.io/medicinaparadiabetes/assets/ssl-Cjd7i8VT.png" alt="SSL Seguridad" />
        </div>

        <!-- Dirección -->
        <div class="mb-8 text-center">
            <div class="flex items-center justify-center gap-2 mb-4">
                <i class="text-3xl fas fa-map-marker-alt lg:text-4xl"></i>
                <a href="https://www.google.com.mx/maps/place/Gutenberg+128,+Anzures,+Miguel+Hidalgo,+11590+Ciudad+de+México,+CDMX" target="_blank" rel="noopener noreferrer" class="text-sm font-bold lg:text-lg hover:underline">
                    Gutenberg #128 Anzures, Miguel Hidalgo, 11590 Ciudad de México
                </a>
            </div>
            <iframe class="w-full h-48 lg:h-72" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3762.5395970522604!2d-99.1760704!3d19.4322888!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x85d1f8b32758939b%3A0xf34fbd07bc47d6dd!2sGutenberg%20128%2C%20Anzures%2C%20Miguel%20Hidalgo%2C%2011590%20Ciudad%20de%20M%C3%A9xico%2C%20CDMX!5e0!3m2!1sen!2smx!4v1730328617197!5m2!1sen!2smx" allowfullscreen="false" loading="lazy" referrerpolicy="no-referrer-when-downgrade" style="border: 0;"></iframe>
        </div>

        <!-- Sección de Contactos -->
        <div class="flex flex-wrap justify-around gap-8 mb-8 text-center">
            <!-- Teléfonos -->
            <div class="flex flex-col items-center">
                <i class="mb-2 text-3xl fas fa-phone"></i>
                <a href="tel:+525563950178" class="px-2 py-1 text-sm font-bold rounded-lg hover:text-rose-500 ">
                    +52 55 6395 0178
                </a>
            </div>
            <div class="flex flex-col items-center">
                <i class="mb-2 text-3xl fas fa-phone"></i>
                <a href="tel:+525563950179" class="px-2 py-1 text-sm font-bold rounded-lg hover:text-rose-500 ">
                    +52 55 6395 0179
                </a>
            </div>

            <!-- Email -->
            <div class="flex flex-col items-center">
                <i class="mb-2 text-3xl fas fa-envelope"></i>
                <a href="mailto:informes@prasadam.mx" class="px-2 py-1 text-sm font-bold rounded-lg hover:text-rose-500 ">
                    informes@prasadam.mx
                </a>
            </div>

            <!-- WhatsApp -->
            <div class="flex flex-col items-center">
                <i class="mb-2 text-3xl fab fa-whatsapp"></i>
                <a href="https://wa.me/525562516687" target="_blank" rel="noopener noreferrer" class="px-2 py-1 text-sm font-bold rounded-lg hover:text-rose-500 ">
                    +52 5562516687
                </a>
            </div>
        </div>

        <!-- Pie de página -->
        <div class="text-center">
            <p class="mb-2 text-sm font-bold lg:text-lg">
                Todos los derechos reservados &copy; {{new Date().getFullYear()}}
            </p>
            <p class="text-sm lg:text-lg">
                Design by <strong>PACA</strong>
            </p>
        </div>
    </footer>


    </div>
</template>

<script lang="ts" setup>
import IntroCard from '@/components/IntroCard.vue';
import { useRoute } from 'vue-router';

const route = useRoute();
</script>

<style scoped>

</style>
