<template>
  <div class="">
    <MainLayout>
      <template #main>
        <section>
          <IntroCard/>
        </section>
        <section class="py-8 font-poppins">
          <h2 class="py-6 mb-6 text-2xl font-bold text-center text-white bg-sky-600 font-poppins">
            Cómo JI Relax Le Ayuda con la Gestión de la Salud muscular y articular
          </h2>
          <section class="flex flex-wrap justify-around w-full gap-2 px-2 mt-5 space-y-3">
            <SmallIntroCard/>
            <SmallIntroCard/>
            <SmallIntroCard/>
            <SmallIntroCard/>
            <SmallIntroCard/>
            <SmallIntroCard/>
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
          <InfoCardMain data-aos="zoom-in-up"  title="Potencia Musculoesquelética"
            summary="Fortalece tu sistema musculoesquelético con ingredientes tradicionales como Ashwagandha y Rasna. Estas hierbas son reconocidas en la medicina ayurvédica por su capacidad para regenerar tejidos dañados, aliviar el estrés muscular y mejorar la recuperación tras lesiones. Este suplemento está formulado para aumentar la resistencia física, prevenir el desgaste de los músculos y proteger los ligamentos. Ideal para quienes buscan mantener un estilo de vida activo y saludable."
            image="https://storage.googleapis.com/a1aa/image/fPJziQLJQMSjdyFrMfbR64dHjPsHEOZ7zOvGkixJheabuOrnA.jpg" />
          <InfoCardMain data-aos="zoom-in-up"  title="Alivio Natural de Dolor"
            summary="Experimenta un alivio eficaz del dolor articular y muscular gracias a la acción sinérgica de Boswellia serrata y Curcuma longa. Estos poderosos ingredientes ayudan a reducir la inflamación, bloqueando enzimas responsables de causar molestias en las articulaciones. Además, alivian el dolor crónico asociado con condiciones como artritis y lesiones deportivas. Este enfoque natural proporciona una alternativa segura y efectiva para mantener tu movilidad sin los efectos secundarios de analgésicos químicos."
            image="https://storage.googleapis.com/a1aa/image/rsmDWdajDbKJHZef3sUQQXrOME7e2ZcO0QYFIurvludjxOrnA.jpg" />
          <InfoCardMain data-aos="zoom-in-up"  title="Flexibilidad Óptima"
            summary="Recupera la flexibilidad perdida en tus articulaciones con la ayuda de Vitex negundo y Ricinus communis. Estas plantas son conocidas por su capacidad para relajar músculos tensos, lubricar las articulaciones y mejorar el rango de movimiento. Al promover la elasticidad natural de los tejidos, esta fórmula es ideal para quienes sufren de rigidez matutina o tienen estilos de vida que requieren constante movimiento."
            image="https://storage.googleapis.com/a1aa/image/BJIOvITonXIFKNdQUMJHTHAfTeCyAkDzOcGvhYQOAXj9Zn1TA.jpg" />
          <InfoCardMain data-aos="zoom-in-up"  title="Bienestar Digestivo"
            summary="Un sistema digestivo saludable es clave para absorber los nutrientes necesarios para huesos y músculos. Este suplemento incluye Lactobacillus sporogenes, un probiótico que mejora la salud intestinal, equilibra la flora bacteriana y promueve una mejor absorción de minerales esenciales como calcio y magnesio. Esto no solo beneficia tu digestión, sino también tu sistema inmunológico y tu vitalidad general."
            image="https://storage.googleapis.com/a1aa/image/Qb1U9O8DSMrMGtVcBOtArC5fE6oSzQ3GIfYlduzWv0Adan1TA.jpg" />
          <InfoCardMain data-aos="zoom-in-up"  title="Protección Antioxidante"
            summary="Combate el envejecimiento celular con antioxidantes naturales provenientes de Curcuma longa y Zingiber officinale. Estos ingredientes ayudan a neutralizar los radicales libres, responsables del daño celular y la inflamación. Su consumo regular puede retrasar el deterioro de huesos y articulaciones, promoviendo una regeneración más rápida de los tejidos. Además, mejoran tu piel y tu sistema inmunológico."
            image="https://storage.googleapis.com/a1aa/image/cBWIbdv6pw6GANUdb6eP3fRow2vwgvRH1dsaMWcOUvJ3an1TA.jpg" />
          <InfoCardMain data-aos="zoom-in-up"  title="Rejuvenecimiento Óseo"
            summary="Mantén tus huesos fuertes y saludables con Shilajit y Boswellia serrata, dos ingredientes clave para prevenir el deterioro óseo. Shilajit, rico en minerales esenciales como calcio y fósforo, estimula la regeneración ósea, mientras que Boswellia reduce la inflamación que afecta las articulaciones. Esta fórmula es ideal para quienes buscan fortalecer su estructura ósea y reducir los riesgos de fracturas."
            image="https://storage.googleapis.com/a1aa/image/t7cBSi2xXq5YBxU1vFiwyHDlIVllv2dKYMvFOSjd6iSQ3Z9E.jpg" />
          <InfoCardMain data-aos="zoom-in-up"  title="Movimiento Sin Límites"
            summary="Recupera la libertad de movimiento con Rasna y Vitex negundo. Estas plantas trabajan para desinflamar las articulaciones, lubricar los cartílagos y reducir las molestias causadas por el desgaste físico. Ideal para personas con trabajos físicamente exigentes, deportistas o quienes sufren de rigidez crónica debido al envejecimiento."
            image="https://storage.googleapis.com/a1aa/image/D4OYWGCnA2Lee0VGP5prsvIL4iL8Ckg9iSG0qffBNNGO2dWPB.jpg" />
          <InfoCardMain data-aos="zoom-in-up"  title="Apoyo en Artritis"
            summary="Maneja eficazmente los síntomas de la artritis con esta mezcla de hierbas diseñada para reducir la inflamación y mejorar la movilidad. Boswellia serrata bloquea los químicos que agravan el dolor, mientras que Curcuma longa trabaja para aliviar la rigidez y mejorar la calidad de vida. Este suplemento es perfecto como complemento de tratamientos médicos para el control de la artritis."
            image="https://storage.googleapis.com/a1aa/image/zN4GuPtbkr50GZJp46lfS81Sxmood9Usxpn2mqdFT3dKvz6JA.jpg" />
          <InfoCardMain data-aos="zoom-in-up"  title="Resistencia Física Mejorada"
            summary="Mejora tu energía y resistencia diaria con Ashwagandha, una hierba adaptógena que equilibra el estrés físico y mental. Esta fórmula ayuda a combatir la fatiga, mejorar el rendimiento físico y acelerar la recuperación muscular tras actividades intensas. Es ideal para deportistas, personas activas y quienes buscan un impulso natural de energía."
            image="https://storage.googleapis.com/a1aa/image/3LdV0aEGAAqdFpNksfn84cBdscC6hinr6djQMQrqvenEfOrnA.jpg" />
          <InfoCardMain data-aos="zoom-in-up"  title="Inflamación Bajo Control"
            summary="Reduce eficazmente la inflamación crónica y aguda con una fórmula basada en Boswellia serrata y Rasna. Estas hierbas actúan directamente sobre las enzimas inflamatorias para aliviar el dolor y mejorar la calidad de vida. Útil para quienes buscan manejar lesiones deportivas o condiciones inflamatorias como la artritis."
            image="https://storage.googleapis.com/a1aa/image/spfnsAQvRkyJSCU064oVai3zJXrt2NuamfNl83lrV4QCgn1TA.jpg" />
          <InfoCardMain data-aos="zoom-in-up"  title="Regeneración Celular"
            summary="Estimula la regeneración celular con una mezcla única de Shilajit y Curcuma longa. Estos ingredientes no solo favorecen la reparación de tejidos musculares y articulares, sino que también promueven la salud general del cuerpo. Ideales para acelerar la recuperación tras lesiones o cirugías."
            image="https://storage.googleapis.com/a1aa/image/LijsZpZeEZ0SHSyTzAGD6EsV7yYepXTqHvcRSDkF0SUdgn1TA.jpg" />
          <InfoCardMain data-aos="zoom-in-up"  title="Equilibrio Holístico"
            summary="Disfruta de un enfoque integral que combina los beneficios de los probióticos y la sabiduría de la Ayurveda. Este suplemento está diseñado para equilibrar tu cuerpo, mejorar tu salud intestinal y fortalecer tu sistema musculoesquelético. Perfecto para quienes buscan una solución natural y efectiva para su bienestar general."
            image="https://storage.googleapis.com/a1aa/image/IOFNwxSs2LrAIxKfEt7OaeYONnOP7FekAVe1n3WKOsLLDeseE.jpg" />
        </section>

        <section class="flex justify-center p-4 px-3 mt-5 text-white bg-cyan-600">
          <h1 class="text-3xl font-bold">
            Flex-Imac Forte, una medicina ayurvedica para mejorar tu estilo de vida
          </h1>
        </section>
        <article class="flex flex-col justify-center">
          <CardInfoSm/>
          <CardInfoSm/>
          <CardInfoSm/>
          <CardInfoSm/>
          <CardInfoSm/>
          <CardInfoSm/>
          <CardInfoSm/>
          <CardInfoSm/>
        </article>

        <!-- <section class="p-6 font-poppins">
          <section class="mb-8">
            <h2 class="mb-4 text-2xl font-bold">
              ¿Qué es la Medicina Ayurvédica?
            </h2>
            <p class="mb-4 font-poppins">
              La medicina ayurvédica, también conocida como Ayurveda, es un sistema de medicina tradicional originario
              de la India. Se basa en la creencia de que la salud y el bienestar dependen del equilibrio entre el
              cuerpo, la mente y el espíritu. Ayurveda utiliza una variedad de técnicas, incluyendo la dieta, el
              ejercicio, la meditación y los tratamientos herbales, para promover la salud y prevenir enfermedades.
            </p>
            <div class="flex space-x-4">
              <div class="flex items-center">
                <i class="mr-2 text-2xl text-green-600 fas fa-leaf">
                </i>
                <span>
                  Natural
                </span>
              </div>
              <div class="flex items-center">
                <i class="mr-2 text-2xl text-red-600 fas fa-heartbeat">
                </i>
                <span>
                  Saludable
                </span>
              </div>
              <div class="flex items-center">
                <i class="mr-2 text-2xl text-blue-600 fas fa-brain">
                </i>
                <span>
                  Equilibrio
                </span>
              </div>
            </div>
          </section>
          <section>
            <h2 class="mb-4 text-2xl font-bold">
              Tratamientos Ayurvédicos
            </h2>
            <div class="grid grid-cols-1 gap-6 md:grid-cols-2 lg:grid-cols-3">
              <div data-aos="zoom-out-up" class="p-4 bg-white rounded-lg shadow-md">
                <img alt="Imagen de hierbas medicinales utilizadas en tratamientos ayurvédicos"
                  class="object-cover w-full h-48 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/sPis2ogsy7YPA5vd2VOlkCs87KbvtQgUxcRoF5zrJdaS6Z9E.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700 font-poppins">
                  Tratamiento Herbal
                </h3>
                <p class="mt-2 font-poppins">
                  Uso de hierbas medicinales para tratar diversas enfermedades y mejorar la salud general. Las hierbas
                  se seleccionan cuidadosamente según las necesidades individuales y se preparan en diversas formas,
                  como tés, cápsulas y extractos.
                </p>
                <div class="flex items-center mt-4">
                  <i class="mr-2 text-xl text-green-600 fas fa-seedling">
                  </i>
                  <span>
                    Hierbas naturales
                  </span>
                </div>
                <div class="flex items-center mt-2">
                  <i class="mr-2 text-xl text-yellow-600 fas fa-prescription-bottle-alt">
                  </i>
                  <span>
                    Sin efectos secundarios
                  </span>
                </div>
              </div>
              <div data-aos="zoom-out-up" class="p-4 bg-white rounded-lg shadow-md">
                <img alt="Imagen de una persona recibiendo un masaje ayurvédico"
                  class="object-cover w-full h-48 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/6FlpEUGfjCSMe0JxhojAwsvBhc9PWpA2OTkFqbKhqRYLpn1TA.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700 font-poppins">
                  Masaje Ayurvédico
                </h3>
                <p class="mt-2 font-poppins">
                  Masajes terapéuticos que ayudan a equilibrar el cuerpo y la mente. Utilizan aceites esenciales y
                  técnicas específicas para aliviar el estrés, mejorar la circulación y promover la relajación profunda.
                </p>
                <div class="flex items-center mt-4">
                  <i class="mr-2 text-xl text-blue-600 fas fa-hands">
                  </i>
                  <span>
                    Relajación profunda
                  </span>
                </div>
                <div class="flex items-center mt-2">
                  <i class="mr-2 text-xl text-purple-600 fas fa-spa">
                  </i>
                  <span>
                    Alivio del estrés
                  </span>
                </div>
              </div>
              <div data-aos="zoom-out-up" class="p-4 bg-white rounded-lg shadow-md">
                <img alt="Imagen de una persona meditando en un entorno natural"
                  class="object-cover w-full h-48 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/nouDCikbY85DE5Rudzo5Jpp4oxpWg85eTsAO7fwsP1EEpn1TA.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700 font-poppins">
                  Meditación
                </h3>
                <p class="mt-2 font-poppins">
                  Prácticas de meditación para reducir el estrés y mejorar el bienestar mental. La meditación ayuda a
                  calmar la mente, aumentar la concentración y promover un estado de paz interior.
                </p>
                <div class="flex items-center mt-4">
                  <i class="mr-2 text-xl text-blue-600 fas fa-brain">
                  </i>
                  <span>
                    Claridad mental
                  </span>
                </div>
                <div class="flex items-center mt-2">
                  <i class="mr-2 text-xl text-red-600 fas fa-heart">
                  </i>
                  <span>
                    Bienestar emocional
                  </span>
                </div>
              </div>
              <div data-aos="zoom-out-up" class="p-4 bg-white rounded-lg shadow-md">
                <img alt="Imagen de una variedad de alimentos saludables, incluyendo frutas, verduras y granos"
                  class="object-cover w-full h-48 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/ZbdH6yb581LRARejM9ncYhfH8kMChYZJxwfwxGzok4RBVPrnA.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700 font-poppins">
                  Dieta Ayurvédica
                </h3>
                <p class="mt-2 font-poppins">
                  Planes de alimentación personalizados para mantener el equilibrio y la salud. La dieta ayurvédica se
                  basa en el uso de alimentos frescos y naturales que se adaptan a las necesidades individuales y ayudan
                  a equilibrar los doshas.
                </p>
                <div class="flex items-center mt-4">
                  <i class="mr-2 text-xl text-red-600 fas fa-apple-alt">
                  </i>
                  <span>
                    Alimentos frescos
                  </span>
                </div>
                <div class="flex items-center mt-2">
                  <i class="mr-2 text-xl text-sky-600 fas fa-carrot">
                  </i>
                  <span>
                    Nutrición balanceada
                  </span>
                </div>
              </div>
              <div data-aos="zoom-out-up" class="p-4 bg-white rounded-lg shadow-md">
                <img alt="Imagen de una persona practicando yoga en un entorno natural"
                  class="object-cover w-full h-48 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/M9HXVu8OX9aXMdHkUlYfjJBT8vWKpjdCabXUTo65JDah0z6JA.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700 font-poppins">
                  Yoga
                </h3>
                <p class="mt-2 font-poppins">
                  Ejercicios físicos y respiratorios para fortalecer el cuerpo y la mente. El yoga combina posturas
                  físicas, técnicas de respiración y meditación para mejorar la flexibilidad, la fuerza y el bienestar
                  general.
                </p>
                <div class="flex items-center mt-4">
                  <i class="mr-2 text-xl text-gray-600 fas fa-dumbbell">
                  </i>
                  <span>
                    Fortalecimiento físico
                  </span>
                </div>
                <div class="flex items-center mt-2">
                  <i class="mr-2 text-xl text-blue-600 fas fa-wind">
                  </i>
                  <span>
                    Mejora de la respiración
                  </span>
                </div>
              </div>
              <div data-aos="zoom-out-up" class="p-4 bg-white rounded-lg shadow-md">
                <img alt="Imagen de una variedad de aceites esenciales" class="object-cover w-full h-48 rounded-t-lg"
                  height="200"
                  src="https://storage.googleapis.com/a1aa/image/d7Zn0Kabv9LIOtPGMQ9qbrzLc1sdP9BvGo4UWocys8kR6Z9E.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700 font-poppins">
                  Aromaterapia
                </h3>
                <p class="mt-2 font-poppins">
                  Uso de aceites esenciales para mejorar el bienestar físico y emocional. La aromaterapia utiliza
                  fragancias naturales para promover la relajación, aliviar el estrés y mejorar el estado de ánimo.
                </p>
                <div class="flex items-center mt-4">
                  <i class="mr-2 text-xl text-yellow-600 fas fa-oil-can">
                  </i>
                  <span>
                    Aceites esenciales
                  </span>
                </div>
                <div class="flex items-center mt-2">
                  <i class="mr-2 text-xl text-green-600 fas fa-smile">
                  </i>
                  <span>
                    Bienestar emocional
                  </span>
                </div>
              </div>
              <div data-aos="zoom-out-up" class="p-4 bg-white rounded-lg shadow-md">
                <img alt="Imagen de una persona recibiendo un tratamiento de Panchakarma"
                  class="object-cover w-full h-48 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/4bfD85ystehekpeVsftyGDNyaaJwKemfCafCLmKmi4IVFBo1TA.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700 font-poppins">
                  Panchakarma
                </h3>
                <p class="mt-2 font-poppins">
                  Un conjunto de cinco terapias que purifican y rejuvenecen el cuerpo. Panchakarma incluye tratamientos
                  como la sudoración, la purgación y la administración de enemas para eliminar toxinas y restaurar el
                  equilibrio.
                </p>
                <div class="flex items-center mt-4">
                  <i class="mr-2 text-xl text-blue-600 fas fa-water">
                  </i>
                  <span>
                    Desintoxicación
                  </span>
                </div>
                <div class="flex items-center mt-2">
                  <i class="mr-2 text-xl text-green-600 fas fa-sync-alt">
                  </i>
                  <span>
                    Rejuvenecimiento
                  </span>
                </div>
              </div>
              <div data-aos="zoom-out-up" class="p-4 bg-white rounded-lg shadow-md">
                <img alt="Imagen de una persona recibiendo un tratamiento de Shirodhara"
                  class="object-cover w-full h-48 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/V5Hl0UVRvLKPNpFpJCIHkkDItsarmS5ylIfS5DtVYeru9n1TA.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700 font-poppins">
                  Shirodhara
                </h3>
                <p class="mt-2 font-poppins">
                  Un tratamiento en el que se vierte aceite tibio en la frente para calmar la mente y el sistema
                  nervioso. Shirodhara es conocido por sus efectos relajantes y su capacidad para mejorar la calidad del
                  sueño.
                </p>
                <div class="flex items-center mt-4">
                  <i class="mr-2 text-xl text-yellow-600 fas fa-oil-can">
                  </i>
                  <span>
                    Aceite tibio
                  </span>
                </div>
                <div class="flex items-center mt-2">
                  <i class="mr-2 text-xl text-blue-600 fas fa-bed">
                  </i>
                  <span>
                    Mejora del sueño
                  </span>
                </div>
              </div>
              <div data-aos="zoom-out-up" class="p-4 bg-white rounded-lg shadow-md">
                <img alt="Imagen de una persona recibiendo un tratamiento de Abhyanga"
                  class="object-cover w-full h-48 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/BKYykEjNudY7EBXCggATyLWT8ArWG0tCAWfxCweNzi2NGo1TA.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700 font-poppins">
                  Abhyanga
                </h3>
                <p class="mt-2 font-poppins">
                  Un masaje ayurvédico con aceite que se aplica en todo el cuerpo. Abhyanga ayuda a mejorar la
                  circulación, eliminar toxinas y promover la relajación y el bienestar general.
                </p>
                <div class="flex items-center mt-4">
                  <i class="mr-2 text-xl text-blue-600 fas fa-hands">
                  </i>
                  <span>
                    Masaje con aceite
                  </span>
                </div>
                <div class="flex items-center mt-2">
                  <i class="mr-2 text-xl text-purple-600 fas fa-spa">
                  </i>
                  <span>
                    Relajación profunda
                  </span>
                </div>
              </div>
              <div data-aos="zoom-out-up" class="p-4 bg-white rounded-lg shadow-md">
                <img alt="Imagen de una persona recibiendo un tratamiento de Nasya"
                  class="object-cover w-full h-48 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/iY0nAQRDedQWBa3dzfAXgWf0yrTAfxxD61U1s2OafKk56AteE.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700 font-poppins">
                  Nasya
                </h3>
                <p class="mt-2 font-poppins">
                  Un tratamiento que implica la administración de aceites medicinales a través de las fosas nasales.
                  Nasya ayuda a limpiar y purificar los senos paranasales, mejorar la respiración y aliviar problemas
                  respiratorios.
                </p>
                <div class="flex items-center mt-4">
                  <i class="mr-2 text-xl text-blue-600 fas fa-wind">
                  </i>
                  <span>
                    Mejora de la respiración
                  </span>
                </div>
                <div class="flex items-center mt-2">
                  <i class="mr-2 text-xl text-green-600 fas fa-lungs">
                  </i>
                  <span>
                    Alivio de problemas respiratorios
                  </span>
                </div>
              </div>
              <div data-aos="zoom-out-up" class="p-4 bg-white rounded-lg shadow-md">
                <img alt="Imagen de una persona recibiendo un tratamiento de Basti"
                  class="object-cover w-full h-48 rounded-t-lg" height="200"
                  src="https://storage.googleapis.com/a1aa/image/77FtRieU8FSOQqf922JMenoJPYQaQe6PVHSBS88gcaC0fAteE.jpg"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700 font-poppins">
                  Basti
                </h3>
                <p class="mt-2 font-poppins">
                  Un tratamiento que implica la administración de enemas medicinales para limpiar y desintoxicar el
                  colon. Basti es eficaz para tratar problemas digestivos y mejorar la salud intestinal.
                </p>
                <div class="flex items-center mt-4">
                  <i class="mr-2 text-xl text-gray-600 fas fa-toilet">
                  </i>
                  <span>
                    Limpieza del colon
                  </span>
                </div>
                <div class="flex items-center mt-2">
                  <i class="mr-2 text-xl text-green-600 fas fa-leaf">
                  </i>
                  <span>
                    Desintoxicación natural
                  </span>
                </div>
              </div>
              <div data-aos="zoom-out-up" class="p-4 bg-white rounded-lg shadow-md">
                <img alt="Imagen de una persona recibiendo un tratamiento de Basti"
                  class="object-cover w-full h-48 rounded-t-lg" height="200"
                  src="https://files.oaiusercontent.com/file-4wDZNkvaAs84nh8NjqfnKE?se=2024-11-29T06%3A23%3A35Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3Db116bfe9-cb33-4b40-9813-619fe8e30731.webp&sig=50NHL/D9Z5jXSwFpZ6T9YLnCaXJ9IPN9jDrnWnzEb4U%3D"
                  width="300" />
                <h3 class="mt-4 text-xl font-bold text-slate-700 font-poppins">
                  Tratamiento Ayurvédico
                </h3>
                <p class="mt-2 font-poppins">
                  Este proceso forma parte de un enfoque holístico para equilibrar la mente y el cuerpo, promoviendo la relajación, la desintoxicación y la sanación. La sesión se lleva a cabo en un entorno tranquilo y sereno, rodeado de elementos naturales como velas, plantas y luz suave, creando una atmósfera pacífica y restauradora para el bienestar general.
                </p>
                <div class="flex items-center mt-4">
                  <i class="mr-2 text-xl text-rose-600 fas fa-heart">
                  </i>
                  <span>
                    Limpieza del colon
                  </span>
                </div>
                <div class="flex items-center mt-2">
                  <i class="mr-2 text-xl text-green-600 fas fa-fire">
                  </i>
                  <span>
                    Desintoxicación natural
                  </span>
                </div>
              </div>
            </div>

          </section>
        </section> -->

        <section class="flex flex-col items-center justify-center w-full min-h-screen font-poppins">
        <div class="w-full mb-8 text-center">
            <h2 class="px-5 py-5 text-2xl font-bold text-white bg-cyan-700">Cómo la Medicina Ayurvédica Puede Ayudar con el Dolor Muscular y Articular</h2>
        </div>
        <div class="flex flex-col items-center w-full max-w-7xl md:flex-row">
            <div class="w-full md:w-1/2">
                <iframe class="w-full rounded-md min-h-80" src="https://www.youtube.com/embed/1T2ngh_RoH4?si=W4O-XMJftstSqCoM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>
            <div class="w-full mt-8 text-center md:w-1/2 md:mt-0 md:ml-8 md:text-left">
                <ul class="list-none list-inside">
                    <li class="mb-2"><i class="text-cyan-500 fas fa-video"></i> En este video se explica cómo la medicina ayurvédica puede ayudar con el dolor muscular y articular.</li>
                    <li class="mb-2"><i class="text-cyan-500 fas fa-leaf"></i> Se detallan los principios básicos de la medicina ayurvédica.</li>
                    <li class="mb-2"><i class="text-cyan-500 fas fa-spa"></i> Se presentan remedios naturales y técnicas de tratamiento.</li>
                    <li class="mb-2"><i class="text-cyan-500 fas fa-lightbulb"></i> Se ofrecen consejos prácticos para incorporar la medicina ayurvédica en la vida diaria.</li>
                    <li class="mb-2"><i class="text-cyan-500 fas fa-utensils"></i> Se discuten los beneficios de la dieta y el estilo de vida ayurvédico.</li>
                </ul>
            </div>
        </div>
    </section>


        <section class="w-full mt-5 font-poppins">
   <h1 class="w-full py-5 mb-6 text-4xl font-bold text-center text-white bg-cyan-800">
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
      <a class="text-sky-500 hover:underline" href="https://www.gob.mx/issste/articulos/el-estres-y-tu-salud?idiom=es" target="_blank">
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
      <a class="text-sky-500 hover:underline" href="https://www.mayoclinic.org/es/healthy-lifestyle/stress-management/in-depth/stress-symptoms/art-20050987" target="_blank">
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
      <a class="text-sky-500 hover:underline" href="https://www.imss.gob.mx/salud-en-linea/estres-laboral" target="_blank">
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
      <a class="text-sky-500 hover:underline" href="https://espanol.womenshealth.gov/mental-health/good-mental-health/stress-and-your-health" target="_blank">
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
      <a class="text-sky-500 hover:underline" href="https://www.topdoctors.es/diccionario-medico/estres/" target="_blank">
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
      <a class="text-sky-500 hover:underline" href="https://cinfasalud.cinfa.com/p/estres/" target="_blank">
       Ver más
      </a>
     </div>
    </div>
   </div>
  </section>
  <section class="p-6 font-poppins">
        <div class="p-6 bg-white rounded-lg shadow-lg">
            <h2 class="mb-4 text-2xl font-bold text-emerald-800">Seguridad de la Página</h2>
            <p class="mb-4 text-gray-700">Nos tomamos muy en serio la seguridad de tu información. Aquí hay algunas medidas que hemos implementado para asegurar que tu experiencia sea segura:</p>

            <!-- Conexión Segura -->
            <div class="flex items-center mb-6">
                <i class="mr-4 text-3xl text-green-500 fas fa-lock"></i>
                <div>
                    <h3 class="text-xl font-semibold">Conexión Segura</h3>
                    <p class="text-gray-600">Utilizamos HTTPS para asegurar que tu conexión a nuestra página esté encriptada y segura. Esto significa que cualquier dato que envíes o recibas a través de nuestra página está protegido contra interceptaciones.</p>
                    <ul class="text-gray-600 list-disc list-inside">
                        <li>Protección contra ataques de intermediarios (Man-in-the-Middle).</li>
                        <li>Encriptación de datos.</li>
                        <li>Verificación de la autenticidad del servidor.</li>
                    </ul>
                </div>
            </div>

            <!-- Certificado SSL -->
            <div class="flex items-center">
                <i class="mr-4 text-3xl text-blue-500 fas fa-shield-alt"></i>
                <div>
                    <h3 class="text-xl font-semibold">Certificado SSL</h3>
                    <p class="text-gray-600">Nuestro sitio está protegido con un certificado SSL, lo que garantiza que tus datos están seguros y encriptados. Un certificado SSL es una tecnología estándar de seguridad que establece un enlace encriptado entre un servidor web y un navegador.</p>
                    <ul class="text-gray-600 list-disc list-inside">
                        <li>Autenticación del sitio web para asegurar que estás comunicándote con el servidor correcto.</li>
                        <li>Encriptación de la información transmitida para protegerla de accesos no autorizados.</li>
                        <li>Confianza y seguridad para nuestros usuarios al ver el candado en la barra de direcciones.</li>
                    </ul>
                </div>
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
                <a href="https://shykandev.github.io/medicinaparahigado/" class="relative w-full h-full" target="_blank"
                  rel="noopener noreferrer">
                  <div
                    class="absolute flex flex-col items-center w-full h-full transition-opacity duration-300 ease-out bg-black opacity-0 hover:opacity-70 justify-evenly">
                    <p class="text-xs font-bold text-center text-white font-poppins md:text-3xl">Jarabe o Cápsulas tu decides</p>
                    <p class="text-sm font-bold text-center text-white font-poppins md:text-3xl">100% Natural</p>
                  </div>
                  <img class="w-full h-full bg-contain rounded-md" src="https://shykandev.github.io/medicinaparahigado/assets/mainHome-BjxRmTRc.jpg" alt="">
                  <p class="absolute text-xs font-bold text-center text-white bg-red-600 top-1 font-poppins md:text-3xl">
                    ¿Problemas en el Hígado?</p>
                  <p class="absolute text-xs font-bold text-center text-white bottom-1 font-poppins md:text-3xl">
                    Conozca Livad</p>
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
</script>

<style scoped></style>
