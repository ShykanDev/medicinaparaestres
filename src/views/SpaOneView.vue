<template>
  <div class="">
    <MainLayout>
      <template #main>
        <h1 class="py-4 mb-8 text-5xl text-center text-white rounded bg-rose-500 font-poppins animate-fade-down">
          Beneficios de Alak Rasayan
          <i class="fas fa-award"></i>
        </h1>
        <div class="container p-4 mx-auto bg-slate-50">

          <div class="flex flex-wrap gap-5 justify-evenly">
                  <BenefitCard v-for="benefit in benefitsData" :key="benefit.title" :title="benefit.title"
              :summary="benefit.summary" :summary2="benefit.summary2" :image="benefit.image"/>
            <!-- :image="benefit.image"  -->
          </div>
        </div>
      </template>
    </MainLayout>
  </div>
</template>

<script lang="ts" setup>
import BenefitCard from '@/components/BenefitCard.vue';
import MainLayout from '@/layouts/MainLayout.vue';

// ingredients data
// const benefitsData = [
//   {
//     title: 'Ashwagandha: El Adaptógeno por Excelencia',
//     summary: `La Ashwagandha (Withania somnifera) es conocida como el "ginseng indio". Es un adaptógeno natural utilizado en la medicina ayurvédica desde hace más de 3,000 años. Su principal función es reducir el estrés y la ansiedad al regular los niveles de cortisol, la hormona del estrés. Estudios científicos han demostrado que puede mejorar la memoria, la concentración y la función cognitiva en general.`,
//     summary2: `Además, la Ashwagandha potencia la resistencia física y la energía, siendo ideal para atletas y personas con fatiga crónica. También apoya la salud hormonal, ayudando a equilibrar las hormonas sexuales, mejorando la fertilidad tanto en hombres como en mujeres. Algunos estudios sugieren que puede fortalecer el sistema inmunológico y ofrecer efectos antiinflamatorios.`
//   },
//   {
//     title: 'Amla: El Superalimento Ayurvédico',
//     summary: `El Amla (Phyllanthus emblica), o grosella espinosa india, es una de las fuentes más ricas de vitamina C natural. Contiene antioxidantes potentes que ayudan a combatir los radicales libres, promoviendo la longevidad celular. Este fruto es esencial en la medicina ayurvédica para fortalecer el sistema inmunológico y mejorar la digestión.`,
//     summary2: `Otros beneficios incluyen la capacidad de mejorar la salud cardiovascular al reducir los niveles de colesterol LDL y triglicéridos. El Amla también es conocido por su impacto en la piel y el cabello, promoviendo una piel radiante y fortaleciendo las raíces del cabello. Su contenido en fibra ayuda a regular el sistema digestivo, previniendo problemas como el estreñimiento.`
//   },
//   {
//     title: 'Prickly Pear: Poder Nutricional del Nopal',
//     summary: `El Prickly Pear (Opuntia ficus-indica), conocido comúnmente como nopal, es una planta suculenta rica en antioxidantes, vitaminas (A, C, K) y minerales como calcio, potasio y magnesio. Su perfil nutricional es ideal para regular los niveles de azúcar en sangre, gracias a su alto contenido en fibra soluble que ralentiza la absorción de glucosa.`,
//     summary2: `Entre sus beneficios más destacados están: la reducción del colesterol LDL, la protección contra enfermedades metabólicas, y su capacidad para reducir la inflamación. El nopal también tiene propiedades hidratantes y reparadoras, apoyando la salud de la piel y promoviendo la regeneración celular. Su consumo regular puede fortalecer el sistema inmunológico y mejorar la salud intestinal.`
//   },
//   {
//     title: 'Boswellia Serrata: El Guerrero Contra la Inflamación',
//     summary: `La Boswellia serrata, conocida como incienso indio, es una resina utilizada durante siglos en la medicina tradicional para combatir la inflamación. Contiene ácidos boswélicos, compuestos que bloquean las enzimas responsables de la inflamación crónica, siendo especialmente eficaz en casos de artritis, osteoartritis y enfermedades inflamatorias intestinales.`,
//     summary2: `Además, esta planta puede mejorar la salud pulmonar, aliviando síntomas de asma y alergias respiratorias. Estudios recientes sugieren que tiene propiedades neuroprotectoras, ayudando en el tratamiento de trastornos neurodegenerativos como el Alzheimer. También se ha utilizado en formulaciones para mejorar la digestión y aliviar el dolor muscular.`
//   },
//   {
//     title: 'Cúrcuma Longa: El Oro de la Naturaleza',
//     summary: `La cúrcuma (Curcuma longa) es una especia ampliamente reconocida por su compuesto activo principal, la curcumina. Este poderoso antioxidante tiene efectos antiinflamatorios significativos, ayudando a aliviar el dolor en afecciones como la artritis y mejorando la movilidad articular. También protege contra el daño celular y el envejecimiento prematuro.`,
//     summary2: `La cúrcuma apoya la salud digestiva al estimular la producción de bilis, mejorando la digestión de grasas. También es conocida por sus beneficios en la salud cerebral, al mejorar la memoria y prevenir el deterioro cognitivo. Su capacidad para fortalecer el sistema inmunológico la convierte en un ingrediente clave en suplementos diseñados para mantener el bienestar general.`
//   }
// ];
const benefitsData = [
  {
    title: 'Reducción del Estrés para una Vida Más Plena',
    summary: `El estrés crónico puede tener un impacto negativo en la salud física y mental. Este enfoque busca reducir los niveles de cortisol, la hormona del estrés, ayudando a tu cuerpo a relajarse y recuperarse de los efectos del día a día. Una mente y cuerpo menos estresados permiten tomar decisiones más claras y disfrutar de una mejor calidad de vida.`,
    summary2: `Alak Rasayan regula la respuesta al estrés, ayudando a equilibrar el sistema nervioso y reduciendo la ansiedad. Esto promueve una relajación duradera, mejora la calidad del sueño y refuerza la salud emocional frente a los desafíos diarios.`,
    image:'https://storage.googleapis.com/a1aa/image/2ae73a59-feea-43e3-9ad0-8ddafeecf891.jpeg'
  },
  {
    title: 'Mejora de la Concentración y el Enfoque Mental',
    summary: `El estrés y la fatiga mental pueden interferir con la capacidad de concentrarse en tareas importantes. Con un enfoque específico en la claridad mental, se estimula la función cognitiva, optimizando la memoria, el aprendizaje y el procesamiento de información. Esto es esencial para mantener la productividad incluso en situaciones desafiantes.`,
    summary2: `Con el uso de Alak Rasayan, se reduce el impacto del estrés en la mente, optimizando la capacidad de concentración y claridad. Esto permite mantener un enfoque relajado incluso en situaciones de alta presión, mejorando la productividad con tranquilidad.`,
    image:'https://storage.googleapis.com/a1aa/image/89c9ed62-7434-468a-b163-f02419192219.jpeg'
  },
  {
    title: 'Promoción de la Relajación Profunda',
    summary: `En un mundo lleno de ruido y actividad constante, encontrar la calma se ha vuelto crucial. Este enfoque ayuda a tu cuerpo a alcanzar un estado de relajación profunda, desacelerando la mente y los latidos del corazón. Al relajarte, disminuyes la tensión muscular y promueves un flujo constante de energía positiva.`,
    summary2: `Alak Rasayan fomenta un estado de relajación profunda, disminuyendo la tensión física y mental. Sus efectos ayudan a crear un ambiente interno de calma, fortaleciendo el cuerpo y la mente para enfrentar el estrés cotidiano.`,
    image:'https://storage.googleapis.com/a1aa/image/a3c6345e-2802-4df4-8658-4aab9db6c079.jpeg'
  },
  {
    title: 'Resiliencia Emocional y Control del Estrés',
    summary: `La resiliencia emocional es la capacidad de mantener la calma y la estabilidad incluso en momentos de alta presión. Este enfoque fomenta una respuesta más saludable al estrés, reduciendo la reactividad emocional y aumentando la capacidad de enfrentar desafíos con claridad y confianza.`,
    summary2: `Al usar Alak Rasayan, se fortalece la resiliencia emocional, ayudando a gestionar el estrés de manera efectiva. Esto no solo reduce la reactividad emocional, sino que también mejora el bienestar general y fomenta una mentalidad más positiva.`,
    image:'https://storage.googleapis.com/a1aa/image/ba1e79ee-f0e5-49f8-b3f7-f0d741d15789.jpeg'
  },
  {
    title: 'Energía Equilibrada y Reducción de la Fatiga',
    summary: `El estrés constante agota la energía, dejando una sensación de cansancio perpetuo. Este enfoque está diseñado para restaurar el equilibrio energético, promoviendo una sensación constante de vitalidad a lo largo del día. Es fundamental mantener una energía estable para afrontar las responsabilidades diarias sin agotarse.`,
    summary2: `Alak Rasayan proporciona una fuente constante de energía equilibrada, combatiendo el agotamiento causado por el estrés. Esto mejora tanto la vitalidad física como la claridad mental, creando un ciclo positivo de relajación y bienestar.`,
    image:'https://storage.googleapis.com/a1aa/image/58186f0c-cbae-48da-93fe-9e8da1ccd6b9.jpeg'
  },
  {
    title: 'Equilibrio entre Mente y Cuerpo',
    summary: `El equilibrio entre la mente y el cuerpo es fundamental para manejar el estrés. Este enfoque fomenta la armonización del sistema nervioso y la regulación de las respuestas fisiológicas al estrés. Con una conexión mente-cuerpo más fuerte, es posible reducir los síntomas de ansiedad, como la tensión muscular, los dolores de cabeza y los problemas digestivos.`,
    summary2: `Alak Rasayan ayuda a armonizar la conexión entre mente y cuerpo, reduciendo los efectos del estrés en el sistema nervioso. Esto favorece un estado de calma, mejorando tanto la relajación física como la claridad emocional.`,
    image:'https://storage.googleapis.com/a1aa/image/bb5040a8-06b9-4c1c-978f-bf60582082a9.jpeg'
  },
  {
    title: 'Sueño Reparador como Base para la Reducción del Estrés',
    summary: `El estrés y el sueño están profundamente conectados. Dormir mal aumenta los niveles de cortisol y disminuye la capacidad de tu cuerpo para manejar el estrés. Este enfoque busca mejorar la calidad del sueño a través de técnicas que promuevan la relajación antes de acostarte y regulen el ciclo de sueño-vigilia.`,
    summary2: `Con Alak Rasayan, el cuerpo entra en un estado de relajación profunda que mejora la calidad del sueño. Esto no solo reduce la fatiga acumulada, sino que también fortalece la capacidad del cuerpo para manejar el estrés de manera más efectiva.`,
    image:'https://storage.googleapis.com/a1aa/image/894cae85-4e5a-4817-98ff-beb4cbaed23e.jpeg'
  },
  {
    title: 'Fortalecimiento del Sistema Nervioso',
    summary: `El sistema nervioso juega un papel crucial en la respuesta al estrés. Este enfoque trabaja para fortalecer el sistema nervioso, ayudándolo a responder de manera más eficiente a situaciones desafiantes sin caer en un estado de sobrecarga. Un sistema nervioso fuerte significa menos agotamiento emocional y físico.`,
    summary2: `Alak Rasayan refuerza el sistema nervioso, ayudándolo a manejar mejor los estímulos estresantes. Esto se traduce en una respuesta más calmada y controlada frente al estrés, apoyando un equilibrio emocional duradero.`,
    image:'https://storage.googleapis.com/a1aa/image/8d83fee3-51ca-4d2d-ae49-b83ac93cc62b.jpeg'
  },
  {
    title: 'Gestión del Estrés en el Entorno Laboral',
    summary: `El estrés relacionado con el trabajo es una de las causas principales de agotamiento emocional. Este enfoque proporciona herramientas para gestionar la presión laboral, establecer límites saludables y desarrollar técnicas para mantener la calma en entornos exigentes.`,
    summary2: `Alak Rasayan reduce los efectos del estrés laboral al promover un estado de calma y concentración. Esto permite mantener un equilibrio saludable entre la vida profesional y personal, mejorando el rendimiento y el bienestar general.`,
    image:'https://storage.googleapis.com/a1aa/image/3414dd37-b84e-412d-bc90-629370e2b747.jpeg'
  },
  {
    title: 'Conexión con la Naturaleza para Aliviar el Estrés',
    summary: `Estar en contacto con la naturaleza tiene un efecto calmante y rejuvenecedor en la mente y el cuerpo. Este enfoque promueve actividades como caminar al aire libre, pasar tiempo en parques o practicar jardinería para reducir los niveles de estrés de manera natural.`,
    summary2: `Alak Rasayan potencia los efectos relajantes del contacto con la naturaleza, ayudando a calmar la mente y reducir el estrés. Su uso regular fortalece la sensación de conexión y tranquilidad, incluso en entornos urbanos.`,
    image:'https://storage.googleapis.com/a1aa/image/8208a7b0-22d8-4ede-aa8d-d86060916c13.jpeg'
  },
  {
    title: 'Reducción de la Ansiedad Social',
    summary: `La ansiedad social puede ser un factor importante de estrés, especialmente en situaciones que requieren interacción constante. Este enfoque trabaja para reducir la tensión emocional que surge en reuniones, presentaciones o eventos sociales, ayudándote a sentirte más relajado y seguro.`,
    summary2: `Alak Rasayan reduce la tensión emocional en situaciones sociales, fomentando una sensación de calma y confianza. Esto permite enfrentar interacciones con menos ansiedad y mayor relajación, mejorando las relaciones personales.`,
    image:'https://storage.googleapis.com/a1aa/image/bd250090-13df-4d19-8b04-5fdb11a698e7.jpeg'
  },
  {
    title: 'Estabilización del Estado de Ánimo',
    summary: `El estrés prolongado puede provocar fluctuaciones en el estado de ánimo, desde irritabilidad hasta tristeza. Este enfoque busca estabilizar las emociones mediante el fortalecimiento de la regulación hormonal y la promoción de neurotransmisores como la serotonina y la dopamina.`,
    summary2: `Alak Rasayan estabiliza las emociones al reducir el impacto del estrés en el estado de ánimo. Esto ayuda a mantener una mentalidad positiva y equilibrada, promoviendo la relajación y una mayor resiliencia emocional.`,
    image:'https://storage.googleapis.com/a1aa/image/0356436f-07db-4fe0-b34d-46878f4761f6.jpeg'
  },
];

</script>

<style scoped></style>
