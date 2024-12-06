<template>
  <div class="">
    <MainLayout>
      <template #main>
        <section>
          <IntroCard/>
        </section>
        <section class="py-8 font-poppins">
          <h2 class="py-6 mb-6 text-2xl font-bold text-center text-white bg-rose-600 font-poppins">
            Alak Rasayan y su efecto para calmar el ESTRÉS
          </h2>
          <section class="flex flex-wrap justify-around w-full gap-2 px-2 mt-5 space-y-3">
            <SmallIntroCard v-for="(item, index) in cardsSmall" :key="index" :item="item" :alt-text="item.altText" :src="item.image" :title="item.title" :image="item.image" :description="item.description" :points="item.points" :summary="item.summary" />
          </section>
          <!-- <div class="container px-4 mx-auto">
            <div class="grid grid-cols-1 gap-6 md:grid-cols-2 lg:grid-cols-3">
              <div data-aos="zoom-out-right"  class="p-6 bg-white rounded-lg shadow-lg">
                <img alt="Imagen de una persona estirándose para mostrar flexibilidad muscular"
                  class="object-cover w-full h-40 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/yr5JQpgflVVfJ0oTeotwz7wetXfWfPqsV9BZk6yBFZ2HaGa9E.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700">
                  Mejora la Flexibilidad Muscular
                </h3>
                <p class="mt-2">
                  Flex-Imac Forte ayuda a mejorar la flexibilidad muscular, permitiéndote moverte con más libertad y
                  comodidad.
                </p>
                <ul class="mt-4">
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Reduce la rigidez muscular
                  </li>
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Mejora el rango de movimiento
                  </li>
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Promueve la relajación muscular
                  </li>
                </ul>
              </div>
              <div data-aos="zoom-out-right" class="p-6 bg-white rounded-lg shadow-lg">
                <img alt="Imagen de una persona sosteniendo su rodilla para mostrar alivio del dolor articular"
                  class="object-cover w-full h-40 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/8ZgUDzoP7VYyF9cjdUTrn8fI3jOJ0vLFhRetfFkeLQC1ghWPB.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700">
                  Alivia el Dolor Articular
                </h3>
                <p class="mt-2">
                  Nuestro suplemento está diseñado para aliviar el dolor articular, haciendo que las actividades diarias
                  sean más manejables.
                </p>
                <ul class="mt-4">
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Reduce la inflamación
                  </li>
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Alivia la incomodidad articular
                  </li>
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Apoya la salud articular
                  </li>
                </ul>
              </div>
              <div data-aos="zoom-out-right" class="p-6 bg-white rounded-lg shadow-lg">
                <img alt="Imagen de una persona levantando pesas para mostrar fuerza muscular"
                  class="object-cover w-full h-40 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/UEPAJlyQeTRLK6srr60pgtOO1u67xn13VVDnuqDRJWePYo1TA.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700">
                  Mejora la Fuerza Muscular
                </h3>
                <p class="mt-2">
                  Flex-Imac Forte ayuda a desarrollar la fuerza muscular, ayudándote a mantenerte activo y fuerte.
                </p>
                <ul class="mt-4">
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Aumenta la resistencia muscular
                  </li>
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Incrementa la potencia muscular
                  </li>
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Apoya la recuperación muscular
                  </li>
                </ul>
              </div>
              <div data-aos="zoom-out-left" class="p-6 bg-white rounded-lg shadow-lg">
                <img alt="Imagen de una persona haciendo yoga para mostrar bienestar general"
                  class="object-cover w-full h-40 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/tPviPpHTcUKyLp0W9TFiCnI110hyuhy9k2jDWjoQurIEGa9E.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700">
                  Promueve el Bienestar General
                </h3>
                <p class="mt-2">
                  Nuestro producto no solo se enfoca en problemas específicos, sino que también promueve el bienestar y
                  la salud en general.
                </p>
                <ul class="mt-4">
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Mejora los niveles de energía
                  </li>
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Apoya la función inmunológica
                  </li>
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Mejora la calidad de vida
                  </li>
                </ul>
              </div>
              <div data-aos="zoom-out-left" class="p-6 bg-white rounded-lg shadow-lg">
                <img alt="Imagen de una persona corriendo para mostrar movilidad mejorada"
                  class="object-cover w-full h-40 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/UhrUVewNjr3hOiarRWenMPruGApgzkPBXzYWeauNrkqmwQrnA.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700">
                  Mejora la Movilidad
                </h3>
                <p class="mt-2">
                  Flex-Imac Forte ayuda a mejorar la movilidad, facilitando la realización de tareas y actividades
                  diarias.
                </p>
                <ul class="mt-4">
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Mejora la flexibilidad articular
                  </li>
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Reduce las restricciones de movimiento
                  </li>
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Promueve un estilo de vida activo
                  </li>
                </ul>
              </div>
              <div data-aos="zoom-out-left" class="p-6 bg-white rounded-lg shadow-lg">
                <img alt="Imagen de una persona masajeando su hombro para mostrar alivio del dolor muscular"
                  class="object-cover w-full h-40 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/7ce2Wd1J4gThViNW7eoXT5OUELKyGRUoEkqRbSBwEv8SYo1TA.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700">
                  Alivia el Dolor Muscular
                </h3>
                <p class="mt-2">
                  Nuestro suplemento es efectivo para aliviar el dolor muscular, proporcionando alivio y comodidad.
                </p>
                <ul class="mt-4">
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Reduce el dolor muscular
                  </li>
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Alivia la tensión muscular
                  </li>
                  <li class="flex items-center">
                    <i class="mr-2 text-green-500 fas fa-check">
                    </i>
                    Promueve la recuperación muscular
                  </li>
                </ul>
              </div>
            </div>
          </div> -->
        </section>

        <section class="flex flex-wrap justify-around w-full gap-2 px-2 mt-5 space-y-3">
          <InfoCardMain data-aos="zoom-in-up" v-for="(info, index) in cardsInfoCardMain" :key="index" :title="info.title" :summary="info.summary" :image="info.image" />
        </section>

        <section class="flex justify-center p-4 px-3 mt-5 text-white bg-rose-600">
          <h1 class="text-3xl font-bold">
            Alak Rasayan, medicina ayurvedica 100% natural
          </h1>
        </section>
        <article class="flex flex-col justify-center">
          <CardInfoSm v-for="(item, index) in cardsInfoSm" :key="index" :description="item.description" :description2="item.description2" :imgTop="item.imgTop" :imgTopPosition="item.imgTopPosition" :imgCenter="item.imgCenter" :imgCenterWidth="item.imgCenterWidth" :title="item.title"/>
        </article>


        <section class="flex flex-col items-center justify-center w-full min-h-screen font-poppins">
        <div class="w-full mb-8 text-center">
            <h2 class="px-5 py-5 text-2xl font-bold text-white bg-rose-700">Cómo la medicina ayurvedica puede ayudarle en la relajación del estrés</h2>
        </div>
        <div class="flex flex-col items-center w-full max-w-7xl md:flex-row">
            <div class="w-full md:w-1/2">
                <iframe class="w-full rounded-md min-h-80" src="https://www.youtube.com/embed/1T2ngh_RoH4?si=W4O-XMJftstSqCoM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
            <div class="w-full mt-8 text-center md:w-1/2 md:mt-0 md:ml-8 md:text-left">
              <ul class="list-none list-inside">
    <li class="mb-2"><i class="text-rose-500 fas fa-video"></i> En este video se habla de cómo la medicina natural ayurvédica ayuda a reducir el estrés y promover el bienestar mental.</li>
    <li class="mb-2"><i class="text-rose-500 fas fa-leaf"></i> Se detallan los principios básicos de la medicina ayurvédica y su enfoque en el equilibrio emocional.</li>
    <li class="mb-2"><i class="text-rose-500 fas fa-spa"></i> Se presentan remedios naturales ayurvédicos para aliviar el estrés y la ansiedad.</li>
    <li class="mb-2"><i class="text-rose-500 fas fa-lightbulb"></i> Se ofrecen consejos prácticos para incorporar la medicina ayurvédica en la vida diaria y reducir el estrés.</li>
    <li class="mb-2"><i class="text-rose-500 fas fa-utensils"></i> Se discuten los beneficios de la dieta y el estilo de vida ayurvédico para mantener una mente tranquila y equilibrada.</li>
</ul>

            </div>
        </div>
    </section>


        <section class="w-full mt-5 font-poppins">
   <h1 class="w-full py-5 mb-6 text-4xl font-bold text-center text-white bg-rose-800">
    Noticias
   </h1>
   <div class="grid grid-cols-1 gap-6 px-2 md:grid-cols-2 lg:grid-cols-3">
    <div class="overflow-hidden bg-white rounded-lg shadow-md border-animated">
     <img alt="Imagen de Noticia 1: Una vista panorámica de una ciudad moderna con rascacielos y un cielo despejado" class="object-cover w-full h-48" height="400" src="https://www.gob.mx/cms/uploads/article/main_image/97543/07_07_20_Estres_Blog_DG.jpg" width="600"/>
     <div class="p-4">
      <h2 class="mb-2 text-xl font-bold">
        El estrés y tu salud
      </h2>
      <p class="mb-4 text-gray-700">
        Si te mareas con frecuencia, tienes problemas para dormir, te sientes cansado todo el tiempo, tienes dolores de cabeza, sufres sobrepeso por comer más de lo normal, estás irritable, tienes tensión muscular o te sientes abrumado, puedes estar sufriendo de estrés.
      </p>
      <a class="text-rose-500 hover:underline" href="https://www.gob.mx/issste/articulos/el-estres-y-tu-salud?idiom=es" target="_blank">
       Ver más
      </a>
     </div>
    </div>
    <div class="overflow-hidden bg-white rounded-lg shadow-md border-animated">
     <img alt="Imagen de Noticia 2: Un grupo de personas en una conferencia, con un orador en el escenario" class="object-cover w-full h-48" height="400" src="https://cuidateplus.marca.com/sites/default/files/styles/natural/public/cms/2024-04/estres.jpg.webp?itok=gCUf_tRs" width="600"/>
     <div class="p-4">
      <h2 class="mb-2 text-xl font-bold">
        Control del estrés
      </h2>
      <p class="mb-4 text-gray-700">
        Los síntomas de estrés pueden estar afectando tu salud, aunque no lo sepas. Puedes culpar a la enfermedad de ese molesto dolor de cabeza, de tus problemas para dormir, de sentirte indispuesto o de tu falta de concentración en el trabajo. Pero es posible que el estrés sea realmente la causa.
      </p>
      <a class="text-rose-500 hover:underline" href="https://www.mayoclinic.org/es/healthy-lifestyle/stress-management/in-depth/stress-symptoms/art-20050987" target="_blank">
       Ver más
      </a>
     </div>
    </div>
    <div class="overflow-hidden bg-white rounded-lg shadow-md border-animated">
     <img alt="Imagen de Noticia 3: Un paisaje natural con montañas y un lago en el fondo" class="object-cover w-full h-48" height="400" src="https://uapa.cuaed.unam.mx/sites/default/files/minisite/static/911f3feb-b698-4c1f-a203-b38dbc741928/estres%20reconocelo/img/1persona_estresada.jpg" width="600"/>
     <div class="p-4">
      <h2 class="mb-2 text-xl font-bold">
        Estrés Laboral
      </h2>
      <p class="mb-4 text-gray-700">
        El 75% de los mexicanos padece fatiga
por estrés laboral, superando a países
como China y Estados Unidos
      </p>
      <a class="text-rose-500 hover:underline" href="https://www.imss.gob.mx/salud-en-linea/estres-laboral" target="_blank">
       Ver más
      </a>
     </div>
    </div>
    <div class="overflow-hidden bg-white rounded-lg shadow-md border-animated">
     <img alt="Imagen de Noticia 4: Un equipo de científicos trabajando en un laboratorio" class="object-cover w-full h-48" height="400" src="https://owh-wh-d9-prod.s3.amazonaws.com/s3fs-public/heading-images/Stressandyourhealth.jpg?VersionId=YQ0yx9xp8I37hW26e7dLu2t19D2XxNpP" width="600"/>
     <div class="p-4">
      <h2 class="mb-2 text-xl font-bold">
        El estrés y tu salud
      </h2>
      <p class="mb-4 text-gray-700">
        El estrés es una reacción a un cambio o desafío. A corto plazo, el estrés puede ser útil. Te hace estar más alerta y te da energía para terminar tus tareas.
      </p>
      <a class="text-rose-500 hover:underline" href="https://espanol.womenshealth.gov/mental-health/good-mental-health/stress-and-your-health" target="_blank">
       Ver más
      </a>
     </div>
    </div>
    <div class="overflow-hidden bg-white rounded-lg shadow-md border-animated">
     <img alt="Imagen de Noticia 5: Un evento deportivo con jugadores en acción en un campo de fútbol" class="object-cover w-full h-48" height="400" src="https://staticnew-prod.topdoctors.es/files/Image/large/a59b88b330de98f8e6986634f2f8cb3d.jpg" width="600"/>
     <div class="p-4">
      <h2 class="mb-2 text-xl font-bold">
        ¿Qué es el estrés?
      </h2>
      <p class="mb-4 text-gray-700">
        El estrés es un estado de tensión física y emocional originado como reacción a una estímulo o presión, ya sea positivo o negativo. Se trata de un estado de defensa que, en pequeñas dosis, ayuda al organismo a reaccionar y adaptarse a los acontecimientos.
      </p>
      <a class="text-rose-500 hover:underline" href="https://www.topdoctors.es/diccionario-medico/estres/" target="_blank">
       Ver más
      </a>
     </div>
    </div>
    <div class="overflow-hidden bg-white rounded-lg shadow-md border-animated">
     <img alt="Imagen de Noticia 6: Una reunión de negocios con personas discutiendo alrededor de una mesa" class="object-cover w-full h-48" height="400" src="https://cdn-cinfasalud.cinfa.com/wp-content/uploads/2015/04/imagen-estres1.jpg?x19187" width="600"/>
     <div class="p-4">
      <h2 class="mb-2 text-xl font-bold">
        ¿Cómo combatir el estrés?
      </h2>
      <p class="mb-4 text-gray-700">
        El estrés puede ser descrito como una situación de sobrecarga o de presión que afecta a una persona y que depende  tanto de las demandas de la situación, como de los recursos de la persona para afrontarla. Así, se trata de un sentimiento de tensión física o emocional que se produce de manera automática y natural ante situaciones o pensamientos que nos resultan amenazadores, frustrantes o desafiantes.
      </p>
      <a class="text-rose-500 hover:underline" href="https://cinfasalud.cinfa.com/p/estres/" target="_blank">
       Ver más
      </a>
     </div>
    </div>
   </div>
  </section>
  <section class="p-6">
   <div class="p-6 bg-white rounded-lg shadow-lg">
    <h2 class="mb-4 text-2xl font-bold text-emerald-800">
     Seguridad de la Página
    </h2>
    <p class="mb-4 text-gray-700">
     Nos tomamos muy en serio la seguridad de tu información. Aquí hay algunas medidas que hemos implementado para asegurar que tu experiencia sea segura:
    </p>
    <!-- Conexión Segura -->
    <div class="flex items-center mb-6">
     <i class="mr-4 text-3xl text-green-500 fas fa-lock">
     </i>
     <div>
      <h3 class="text-xl font-semibold">
       Conexión Segura
      </h3>
      <p class="text-gray-600">
       Utilizamos HTTPS para asegurar que tu conexión a nuestra página esté encriptada y segura. Esto significa que cualquier dato que envíes o recibas a través de nuestra página está protegido contra interceptaciones.
      </p>
      <ul class="text-gray-600 list-disc list-inside">
       <li>
        Protección contra ataques de intermediarios (Man-in-the-Middle).
       </li>
       <li>
        Encriptación de datos.
       </li>
       <li>
        Verificación de la autenticidad del servidor.
       </li>
      </ul>
     </div>
     <img alt="Icono de un candado verde que representa una conexión segura" class="ml-4" height="100" src="https://storage.googleapis.com/a1aa/image/f21V9eTaZnkJJEQaDbM3NgOGnIYdFgqFAAYplLZ8763Pz83TA.jpg" width="100"/>
    </div>
    <!-- Certificado SSL -->
    <div class="flex items-center mb-6">
     <i class="mr-4 text-3xl text-blue-500 fas fa-shield-alt">
     </i>
     <div>
      <h3 class="text-xl font-semibold">
       Certificado SSL
      </h3>
      <p class="text-gray-600">
       Nuestro sitio está protegido con un certificado SSL, lo que garantiza que tus datos están seguros y encriptados. Un certificado SSL es una tecnología estándar de seguridad que establece un enlace encriptado entre un servidor web y un navegador.
      </p>
      <ul class="text-gray-600 list-disc list-inside">
       <li>
        Autenticación del sitio web para asegurar que estás comunicándote con el servidor correcto.
       </li>
       <li>
        Encriptación de la información transmitida para protegerla de accesos no autorizados.
       </li>
       <li>
        Confianza y seguridad para nuestros usuarios al ver el candado en la barra de direcciones.
       </li>
      </ul>
     </div>
     <img alt="Icono de un escudo azul que representa un certificado SSL" class="ml-4" height="100" src="https://storage.googleapis.com/a1aa/image/UCJ2MlEK89KYBpVAlJRY7D6WlqGzcm8EYw2ZLCeYk1vmZe3TA.jpg" width="100"/>
    </div>

    <!-- Monitoreo Constante -->
    <div class="flex items-center">
     <i class="mr-4 text-3xl text-yellow-500 fas fa-eye">
     </i>
     <div>
      <h3 class="text-xl font-semibold">
       Monitoreo Constante
      </h3>
      <p class="text-gray-600">
       Nuestro equipo de seguridad monitorea constantemente nuestra infraestructura para detectar y prevenir cualquier actividad sospechosa.
      </p>
      <ul class="text-gray-600 list-disc list-inside">
       <li>
        Detección de intrusiones.
       </li>
       <li>
        Alertas de seguridad en tiempo real.
       </li>
       <li>
        Actualizaciones regulares de seguridad.
       </li>
      </ul>
     </div>
     <img alt="Icono de un ojo amarillo que representa el monitoreo constante" class="ml-4" height="100" src="https://storage.googleapis.com/a1aa/image/4sw54wFjh5beN6b13AhimUXbhetle6N1Ua0njxIKtWckm5vnA.jpg" width="100"/>
    </div>
   </div>
  </section>
                     <!-- Ads Section -->
                     <h3 class="mt-6 text-2xl font-bold text-center text-rose-900 font-poppins">Le puede interesar</h3>
        <section  class="flex justify-center w-full my-6 space-x-4"> <!-- ads section -->
              <div
                class="relative flex items-center justify-center w-1/2 p-4 border-2 rounded-lg shadow-md border-slate-400 bg-slate-100">
                <span
                  class="absolute px-2 py-1 text-sm font-semibold text-white rounded -top-4 left-4 bg-slate-500">Anuncio</span>
                <a href="https://medicinaparaartritis.com/" class="relative w-full h-full" target="_blank"
                  rel="noopener noreferrer">
                  <div
                    class="absolute flex flex-col items-center w-full h-full transition-opacity duration-300 ease-out bg-black opacity-0 hover:opacity-70 justify-evenly">
                    <p class="text-xs font-bold text-center text-white font-poppins md:text-3xl">Jarabe o Cápsulas tu decides</p>
                    <p class="text-sm font-bold text-center text-white font-poppins md:text-3xl">100% Natural</p>
                  </div>
                  <img class="w-full h-full bg-contain rounded-md" src="https://i.ibb.co/0mJT1NQ/flexImac.jpg" alt="">
                  <p class="absolute text-xs font-bold text-center text-white bg-sky-600 top-1 font-poppins md:text-3xl">
                    ¿Dolor Articular o Muscular?</p>
                  <p class="absolute text-xs font-bold text-center text-white bottom-1 font-poppins md:text-3xl">
                    Conozca FLEX-IMAC FORTE</p>
                </a>
              </div>

              <div
                class="relative flex items-center justify-center w-1/2 p-4 border-2 rounded-lg shadow-md border-slate-400 bg-slate-100">
                <span
                  class="absolute px-2 py-1 text-sm font-semibold text-white rounded -top-4 left-4 bg-slate-500">Anuncio</span>
                <a href="https://shykandev.github.io/medicinaparadiabetes/" class="relative w-full h-full" target="_blank"
                  rel="noopener noreferrer">
                  <div
                    class="absolute flex flex-col items-center w-full h-full transition-opacity duration-300 ease-out bg-black opacity-0 hover:opacity-70 justify-evenly">
                    <p class="text-sm font-bold text-center text-white font-poppins md:text-3xl">100% Natural</p>
                    <!-- <p class="text-sm font-bold text-center text-white font-poppins md:text-3xl">Tu </p> -->
                    <p class="hidden text-sm font-bold text-center text-white font-poppins md:text-3xl md:block">Esta es su solución</p>
                  </div>
                  <img class="w-full h-full bg-contain rounded-md" src="https://shykandev.github.io/medicinaparadiabetes/assets/mainHome-EGZr2Qar.jpg" alt="">
                  <p class="absolute top-0 text-xs font-bold text-center text-white bg-yellow-600 font-poppins md:text-3xl">¿Tienes Diabetes?</p>
                  <p
                    class="absolute px-3 text-xs font-bold text-center text-white md:px-0 bottom-3 font-poppins md:text-3xl">
                    Le recomendamos GLUFAC</p>
                </a>
              </div>
            </section>
      </template>
    </MainLayout>
  </div>
</template>

<script lang="ts" setup>
import MainLayout from '@/layouts/MainLayout.vue';
import InfoCardMain  from '@/components/InfoCardMain.vue';
import IntroCard from '@/components/IntroCard.vue';
import SmallIntroCard from '@/components/SmallIntroCard.vue';
import CardInfoSm from '@/components/CardInfoSm.vue';

const cardsSmall = [
  {
    image: "https://storage.googleapis.com/a1aa/image/c163bd09-376e-4026-a254-66e8847102bb.jpeg",
    altText: "Imagen para relajación y bienestar",
    title: "Mejora tu bienestar emocional",
    description: "Esta fórmula natural ayuda a reducir el estrés, promoviendo un estado de calma y equilibrio mental para mejorar el bienestar emocional.",
    points: [
      "Alivia el estrés y la ansiedad.",
      "Promueve la calma y la relajación.",
      "Mejora el enfoque y claridad mental.",
    ],
    summary: "Una solución perfecta para aquellos que buscan mantener la serenidad mental en situaciones de estrés y ansiedad.",
  },
  {
    image: "https://storage.googleapis.com/a1aa/image/da80da1f-5b2a-42e9-b09a-0d069ed2bb37.jpeg",
    altText: "Imagen para salud inmunológica",
    title: "Reduce los niveles de cortisol, (la hormona del estrés)",
    description: "Con propiedades adaptógenas y relajantes, esta mezcla natural ayuda a equilibrar los niveles de cortisol, promoviendo la calma y reduciendo el impacto del estrés en el cuerpo.",
points: [
  "Equilibra el cortisol, la hormona del estrés.",
  "Promueve la relajación y el bienestar general.",
  "Aumenta la capacidad del cuerpo para manejar el estrés.",
],
summary: "Perfecto para reducir el estrés y mantener un equilibrio hormonal saludable, ayudando al cuerpo a relajarse y recuperarse de manera natural.",
  },
  {
    image: "https://storage.googleapis.com/a1aa/image/96b43687-ddf5-40ef-be8b-fbbf5b95f511.jpeg",
    altText: "Imagen para bienestar digestivo y hormonal",
    title: "Equilibra tu cuerpo y tu mente",
    description: "Esta mezcla apoya la salud digestiva mientras ayuda a reducir el cortisol, promoviendo energía, calma y bienestar general.",
    points: [
        "Equilibra el cortisol para reducir el estrés.",
        "Mejora la digestión y la absorción de nutrientes.",
        "Aumenta la energía y combate la fatiga asociada al estrés.",
    ],
    summary: "Un sistema digestivo saludable y niveles equilibrados de cortisol son clave para sentirte con energía, relajado y en armonía.",
},
  {
    image: "https://storage.googleapis.com/a1aa/image/f04d8e27-a081-46c4-9f15-49da69a1e791.jpeg",
    altText: "Imagen para claridad mental",
    title: "Aumenta tu claridad mental y enfoque",
    description: "Ideal para mejorar la concentración y la claridad mental, ayudando a mantenerte enfocado durante largas horas y a combatir la fatiga mental.",
    points: [
      "Aumenta la concentración y enfoque.",
      "Combate la fatiga mental y física.",
      "Mejora la claridad mental y la memoria.",
    ],
    summary: "Perfecto para quienes buscan optimizar su rendimiento intelectual y mantener un enfoque claro y productivo durante el día.",
  },
  {
    image: "https://storage.googleapis.com/a1aa/image/64f0751a-9ea1-4df4-8a61-2825a082ac8a.jpeg",
    altText: "Imagen para aliviar el estrés",
    title: "Relaja cuerpo y mente de forma natural",
    description: "Esta combinación natural ofrece una relajación profunda tanto a nivel físico como emocional, reduciendo el estrés y mejorando tu calidad de vida.",
    points: [
      "Reduce el estrés y mejora el ánimo.",
      "Promueve una relajación profunda.",
      "Alivia las tensiones musculares y emocionales.",
    ],
    summary: "Perfecto para quienes buscan relajarse de manera natural, aliviando tanto la tensión física como la mental.",
  },
  {
    image: "https://storage.googleapis.com/a1aa/image/e2da7490-9027-4235-a9b8-2ea6b1b3eb0b.jpeg",
    altText: "Imagen para salud antiinflamatoria",
    title: "Propiedades antiinflamatorias para tu cuerpo",
    description: "Con propiedades antiinflamatorias, esta mezcla ayuda a reducir las molestias y dolores, al mismo tiempo que mejora la salud general y el bienestar.",
    points: [
      "Reduce la inflamación y el dolor.",
      "Promueve la salud articular y muscular.",
      "Aumenta la movilidad y flexibilidad.",
    ],
    summary: "Ideal para quienes necesitan aliviar la inflamación y promover una recuperación rápida de lesiones o molestias crónicas.",
  }
];

const cardsInfoCardMain = [
  {
    title: 'Alivio natural para el estrés y la ansiedad',
    summary: 'La combinación de Ashwagandha (30%), Amla (30%) y Prickly Pear (30%) trabaja sinérgicamente para reducir el estrés crónico y la ansiedad, mejorando la respuesta del cuerpo ante situaciones de presión. Ashwagandha, como adaptógeno natural, ayuda a equilibrar los niveles de cortisol, la hormona del estrés, promoviendo una sensación de calma y relajación. Amla y Prickly Pear refuerzan el sistema inmunológico y reducen la tensión muscular, lo que contribuye a un estado de bienestar general.',
    image: 'https://storage.googleapis.com/a1aa/image/243ef63d-828e-4f4a-baf5-ad0322a0630e.jpeg',
  },
  {
    title: 'Reduce las migrañas provocadas por el estrés',
    summary: 'El estrés es una de las principales causas de migrañas y dolores de cabeza. Ashwagandha actúa aliviando la tensión muscular y reduciendo la inflamación, mientras que Amla aporta sus propiedades antiinflamatorias, ayudando a reducir la frecuencia y la intensidad de las migrañas. Prickly Pear, por su parte, ofrece un alivio antioxidante que mejora la circulación sanguínea en el cerebro, ayudando a minimizar los síntomas de las migrañas inducidas por el estrés.',
    image: 'https://storage.googleapis.com/a1aa/image/3952302f-2689-4f0a-8fd1-616f4eb06c31.jpeg',
  },
  {
    title: 'Mejora el sueño y combate el insomnio',
    summary: 'Cuando el estrés afecta nuestras noches, el sueño se ve comprometido. Ashwagandha favorece la relajación del sistema nervioso, ayudando a reducir el insomnio relacionado con altos niveles de ansiedad y tensión. Además, Amla ayuda a regular el ciclo circadiano gracias a sus propiedades antioxidantes, mientras que Prickly Pear alivia los síntomas digestivos que pueden interrumpir el descanso. Esta combinación promueve un sueño profundo y reparador, crucial para la recuperación del cuerpo.',
    image: 'https://storage.googleapis.com/a1aa/image/ea3b7633-2d02-445b-a122-e211bc94c08f.jpeg',
  },
  {
    title: 'Aumenta la energía mental y física',
    summary: 'El estrés crónico puede agotarnos tanto mental como físicamente. Ashwagandha es conocida por aumentar la energía y la vitalidad, mientras reduce la fatiga causada por el estrés. Amla mejora la claridad mental y la concentración, lo que ayuda a superar los bloqueos mentales generados por la ansiedad. Prickly Pear, con sus propiedades desintoxicantes, limpia el cuerpo de toxinas acumuladas durante períodos de estrés intenso, mejorando tanto la energía física como mental.',
    image: 'https://storage.googleapis.com/a1aa/image/6235f164-249d-44c5-bfb3-f3524e751039.jpeg',
  },
  {
    title: 'Refuerza el sistema inmunológico bajo estrés',
    summary: 'El estrés prolongado debilita el sistema inmunológico, haciendo que el cuerpo sea más susceptible a enfermedades. Amla, rica en vitamina C, refuerza las defensas del cuerpo, mientras que Ashwagandha ayuda a equilibrar el sistema hormonal y a reducir el impacto negativo del estrés en el sistema inmunológico. Prickly Pear aporta antioxidantes que combaten los efectos del estrés oxidativo, promoviendo una mayor resistencia a enfermedades y mejorando la recuperación.',
    image: 'https://storage.googleapis.com/a1aa/image/5a845d91-046c-4083-9c71-ad5ed4a933fa.jpeg',
  },
  {
    title: 'Alivio para la tensión muscular y dolores por estrés',
    summary: 'El estrés puede causar tensiones musculares crónicas que resultan en dolores físicos. Ashwagandha ayuda a aliviar la tensión muscular al equilibrar los niveles hormonales, mientras que Amla y Prickly Pear proporcionan propiedades antiinflamatorias y relajantes. Juntas, estas plantas ofrecen un enfoque natural para liberar la tensión acumulada, aliviando dolores de espalda, cuello y hombros causados por el estrés.',
    image: 'https://storage.googleapis.com/a1aa/image/2b9d5e44-2989-452a-bcd0-599657677209.jpeg',
  },
];

const cardsInfoSm = [
{
    title: 'Equilibrio mental para aliviar el estrés',
    description: 'Las propiedades adaptógenas de Ashwagandha ayudan a regular la respuesta del cuerpo ante el estrés, promoviendo un equilibrio emocional. Junto con Amla, que es rica en antioxidantes, y Prickly Pear, conocido por sus beneficios antiinflamatorios, esta combinación proporciona una protección integral contra el desgaste mental causado por el estrés constante.',
    description2: 'Esta mezcla no solo ayuda a reducir los efectos negativos del estrés, sino que también mejora la claridad mental y la capacidad de concentración, permitiendo un mejor rendimiento durante el día.',
    imgTop: 'https://example.com/image1.jpg',
    imgTopPosition: 'left',
    showImgTop: true,
    imgCenter: 'https://storage.googleapis.com/a1aa/image/2e8fc544-5036-4bc0-a481-489aeac82366.jpeg',
    imgCenterWidth: 'w-20',
    showImgCenter: true,
  },
  {
    title: 'Reducción de tensión nerviosa y estrés emocional',
    description: 'El estrés emocional y la tensión nerviosa son comunes hoy en día. Ashwagandha es excelente para restaurar el equilibrio del sistema nervioso, mientras que Amla aporta un apoyo antioxidante que refuerza el sistema inmunológico y ayuda a aliviar la ansiedad. Prickly Pear complementa este efecto reduciendo la inflamación en el cuerpo, lo que ayuda a liberar la tensión acumulada.',
    description2: 'La combinación de estas plantas no solo combate la ansiedad, sino que también ayuda a restaurar la calma en situaciones de alta presión, mejorando el estado de ánimo general.',
    imgTop: 'https://example.com/image2.jpg',
    imgTopPosition: 'right',
    showImgTop: true,
    imgCenter: 'https://storage.googleapis.com/a1aa/image/15e9055a-dfa4-4eea-a6e9-dfa3c9546fb0.jpeg',
    imgCenterWidth: 'w-32',
    showImgCenter: true,
  },
  {
    title: 'Recuperación del bienestar físico y mental',
    description: 'El estrés constante puede agotar tanto la mente como el cuerpo. Ashwagandha es conocida por su capacidad para restaurar los niveles de energía y vitalidad, mientras que Amla ayuda a restaurar el equilibrio emocional. Prickly Pear, con su efecto desintoxicante, favorece la circulación sanguínea, reduciendo los efectos secundarios del estrés en el sistema cardiovascular y nervioso.',
    description2: 'Esta combinación proporciona un enfoque integral para recuperar tanto la energía mental como física, mejorando el bienestar general y ayudando a superar el agotamiento relacionado con el estrés.',
    imgTop: 'https://example.com/image3.jpg',
    imgTopPosition: 'center',
    showImgTop: true,
    imgCenter: 'https://storage.googleapis.com/a1aa/image/326e5dbd-00a9-44b6-97e9-8313fb02f12e.jpeg',
    imgCenterWidth: 'w-24',
    showImgCenter: true,
  },
  {
    title: 'Fortalecimiento del sistema nervioso ante el estrés',
    description: 'El estrés prolongado afecta profundamente al sistema nervioso. Ashwagandha es conocida por su capacidad para restaurar el equilibrio en el sistema nervioso, mientras que Amla refuerza las defensas del cuerpo. Prickly Pear reduce la inflamación en las células nerviosas, ayudando a reducir los efectos negativos del estrés en la salud cerebral y física.',
    description2: 'Esta mezcla actúa como un tónico natural para el sistema nervioso, ayudando a prevenir los efectos a largo plazo del estrés, como la fatiga y el agotamiento mental.',
    imgTop: 'https://example.com/image4.jpg',
    imgTopPosition: 'left',
    showImgTop: true,
    imgCenter: 'https://storage.googleapis.com/a1aa/image/c396fdf8-76d5-4454-b776-7680ccb6b64c.jpeg',
    imgCenterWidth: 'w-28',
    showImgCenter: true,
  },
]

</script>

<style scoped></style>
