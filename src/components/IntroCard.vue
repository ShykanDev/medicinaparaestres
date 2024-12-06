<template>
<section class="p-4 bg-gradient-to-r from-rose-700 via-red-500 to-rose-700">
  <article class="flex flex-col-reverse items-center justify-between gap-8 p-6 bg-white rounded-lg shadow-lg md:flex-row md:gap-16 md:p-10 bg-opacity-90">
    <!-- Contenedor de texto -->
    <div class="p-4 mx-auto bg-white ">
          <div class="flex flex-col md:flex-row animate-fade">
            <div class="p-2 md:w-1/2">
              <img alt="A woman sitting on a bed looking upset while a man lies next to her"
                class="w-full border-4 rounded-xl border-rose-200 md:min-h-[65dvh]" src="https://images.pexels.com/photos/133021/pexels-photo-133021.jpeg?auto=compress&cs=tinysrgb&w=600" />
            </div>
            <div class="p-2 md:w-1/2">
              <h1 class="text-4xl font-bold leading-tight text-rose-600">
                Sea libre del estrés y la ansiedad, y encuentre la paz interior con <span class="italic font-bold underline text-rose-500 font-poppins">ALAK RASAYAN</span>
              </h1>

              <div class="mt-4">
                <div class="flex flex-col text-xl font-semibold font-poppins text-rose-900">
                  <p class="animate-fade-left ">Medicina ayurvédica</p>
                  <p class="animate-fade-left animate-delay-200">con origen milenario</p>
                  <p class="animate-fade-left animate-delay-500">en la India</p>
                </div>
                <div class="flex justify-center mt-4 font-semibold font-poppins animate-fade-left animate-delay-700">
                  <img src="https://i.ibb.co/VqZ4mch/saint-Indian-removebg-preview.png" alt="" class="w-28">
                </div>


                <!-- <div class="flex mt-2 space-x-2">
                  <a href="https://www.facebook.com/AyurevedaPrasadam?modal=admin_todo_tour" target="_blank"
                    rel="noopener noreferrer"
                    class="flex items-center px-4 py-2 text-blue-600 border border-blue-200 rounded">
                    <v-icon name="co-facebook" class="mr-2 text-[#1877f2]"></v-icon>

                  </a>
                  <a href="https://twitter.com/_prasadam_" target="_blank" rel="noopener noreferrer"
                    class="flex items-center px-4 py-2 text-blue-600 border border-blue-200 rounded">
                    <v-icon name="co-twitter" class="mr-2 text-[#1da1f2]"></v-icon>

                  </a>

                  <a href="https://api.whatsapp.com/send/?phone=525562516687&text&type=phone_number&app_absent=0" class="flex items-center px-4 py-2 text-blue-600 border border-blue-200 rounded" target="_blank" rel="noopener noreferrer">
                    <v-icon name="co-whatsapp" class="mr-2 text-[#25d366]"></v-icon>

                  </a>
                  <a href="https://www.instagram.com/_prasadam_/?hl=es-la" target="_blank" rel="noopener noreferrer"
                    class="flex items-center px-4 py-2 text-blue-600 border border-blue-200 rounded">
                    <v-icon name="co-instagram" class="mr-2 text-[#fa6060]"></v-icon>

                  </a>
                </div> -->
              </div>

            </div>
          </div>
          <div class="flex justify-around font-poppins">
              <p class="px-2 py-2 text-white rounded-lg bg-emerald-600">100% natural <i class="fas fa-leaf" ></i></p>
              <p class="px-2 py-2 text-white bg-yellow-600 rounded-lg">Sin químicos <i class="fas fa-ban"></i></p>
              <p class="px-2 py-2 text-white rounded-lg bg-rose-800">Adiós al estrés <i class="fas fa-spa"></i></p>
            </div>
        </div>

    <!-- Imagen del producto -->
    <img
      src="https://i.ibb.co/gVCMz0L/IMG-20241206-WA0018.jpg"
      alt="Imagen representativa de InstaGo"
      class="w-full mt-6 rounded-lg shadow-md md:w-1/2 md:mt-0 animate-fade"
    />
  </article>

  <!-- Sección de imágenes en grid con títulos -->
  <!-- <section class="flex grid flex-col-reverse grid-cols-1 gap-6 p-4 mt-8 bg-white rounded-lg shadow-md sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 md:gap-8 bg-opacity-90 md:mt-0 md:flex-col">
    <div class="relative overflow-hidden rounded-lg shadow-lg">
      <img src="https://files.oaiusercontent.com/file-71wLV49UkWyoA3AL4nsq6r?se=2024-11-29T23%3A09%3A17Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3D57b746b8-fe71-45d9-a3f9-7ac1e80e22a4.webp&sig=CmlG1W4N9ftuIv9K9xm3uth0WKr%2BGPWNlRz0foDhR24%3D" alt="Problemas de relación" class="object-cover w-full h-full rounded-lg">
      <h2 class="absolute bottom-0 left-0 right-0 p-4 text-center text-white bg-black bg-opacity-50">Alivio al dolor de espalda</h2>
    </div>

    <div class="relative overflow-hidden rounded-lg shadow-lg">
      <img src="https://storage.googleapis.com/a1aa/image/vQmvgmEt6xYaNlMXBy1zhLE6sRf9eAq4V7JbfkU7RGfobeveE.jpg" alt="Conflicto de pareja" class="object-cover w-full h-full rounded-lg">
      <h2 class="absolute bottom-0 left-0 right-0 p-4 text-center text-white bg-black bg-opacity-50">Solución al dolor de rodilla</h2>
    </div>

    <div class="relative overflow-hidden rounded-lg shadow-lg">
      <img src="https://storage.googleapis.com/a1aa/image/y0VncefBlokgF0K6HgxRkE5ftyBNabmmdHGf77RDSCYvgeveE.jpg" alt="Dificultades sexuales" class="object-cover w-full h-full rounded-lg">
      <h2 class="absolute bottom-0 left-0 right-0 p-4 text-center text-white bg-black bg-opacity-50">Alivio al dolor articular de manos</h2>
    </div>

    <div class="relative overflow-hidden rounded-lg shadow-lg">
      <img src="https://storage.googleapis.com/a1aa/image/x17JIXDx614KDFmnX8sG5GLhJWvCTpGyk1adOJ6eSd8M0f1TA.jpg" alt="Tensión en la relación" class="object-cover w-full h-full rounded-lg">
      <h2 class="absolute bottom-0 left-0 right-0 p-4 text-center text-white bg-black bg-opacity-50">Solución al dolor muscular de cuello</h2>
    </div>
  </section> -->
</section>






</template>

<script lang="ts" setup>

</script>

<style scoped>

</style>
