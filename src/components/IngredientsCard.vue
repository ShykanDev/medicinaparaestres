<template>
    <div class="">
      <div class="max-w-sm mx-auto my-6">
  <ul class="flex flex-col space-y-6">
    <li class="flex justify-center">
      <div class="overflow-hidden transition-transform duration-300 transform rounded-lg shadow-lg card bg-gradient-to-r from-pink-50 via-red-50 to-yellow-50 hover:scale-105">
        <div class="relative w-full h-56 overflow-hidden rounded-t-lg card_image">
          <!-- img -->
          <img :src="imgSrc" alt="imagen ingrediente" class="object-cover w-full h-full" />
          <!-- Optional price tag -->
          <!-- <span class="absolute px-4 py-1 text-sm font-bold text-black bg-white rounded-full top-2 right-2">$9</span> -->
        </div>
        <div class="p-6 text-black card_content">
          <!-- Main title -->
          <h2 class="mb-4 text-2xl font-bold card_title text-rose-800">{{ mainTitle }}</h2>
          <div class="space-y-4 card_text">
            <!-- Small intro -->
            <p class="text-lg font-poppins">{{ smallIntro }}</p>
            <hr class="mb-4 border-white" />
            <!-- Description -->
            <p class="font-poppins">{{ description }}</p>
            <hr class="mb-4 border-white" />
            <!-- List info -->
            <ul class="space-y-2">
              <li v-for="item in infoArr" :key="item.id" class="text-sm">
                <strong class="text-rose-700">{{ item.property }}:</strong> {{ item.description }}
              </li>
            </ul>
          </div>
        </div>
      </div>
    </li>
  </ul>
</div>

    </div>
</template>

<script lang="ts" setup>

interface InfoItem {
  id: number,
  property: string,
  description: string
}


const props = defineProps({
  mainTitle: String,
  smallIntro: String,
  description: String,
  imgSrc: String,
  infoArr:{
    type: Array <InfoItem>,
  },
  titleColor: String
})

</script>

<style scoped>

*,
*::before,
*::after {
  box-sizing: border-box;
}


.cards {
  display: flex;
  flex-wrap: wrap;
  list-style: none;
  margin: 0;
  padding: 0;
}

.cards_item {
  display: flex;
  padding: 1rem;
}

.card_image {
  position: relative;
  max-height: 250px;
}

.card_image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.card_price {
  position: absolute;
  bottom: 8px;
  right: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 45px;
  height: 45px;
  border-radius: 0.25rem;
  background-color: #c83f54;
  font-size: 18px;
  font-weight: 700;
}

.card_price span {
  font-size: 12px;
  margin-top: -2px;
}

.note {
  position: absolute;
  top: 8px;
  left: 8px;
  padding: 4px 8px;
  border-radius: 0.25rem;
  background-color: #cd2252;
  font-size: 14px;
  font-weight: 700;
}


.card {
  background-color: white;
  border-radius: 0.25rem;
  box-shadow: 0 20px 40px -14px rgba(0, 0, 0, 0.25);
  display: flex;
  flex-direction: column;
  /* overflow: hidden; */
}

.card_content {
  position: relative;
  padding: 16px 12px 32px 24px;
  margin: 16px 8px 8px 0;
  /* max-height: 290px; */
  /* overflow-y: scroll; */
}

.card_content::-webkit-scrollbar {
  width: 8px;
}

.card_content::-webkit-scrollbar-track {
  box-shadow: 0;
  border-radius: 0;
}

.card_content::-webkit-scrollbar-thumb {
  background: #c83f3f;
  border-radius: 15px;
}

.card_title {
  position: relative;
  margin: 0 0 24px;
  padding-bottom: 10px;
  text-align: center;
  font-size: 20px;
  font-weight: 700;
}

.card_title::after {
  position: absolute;
  display: block;
  width: 50px;
  height: 2px;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  background-color: #dd3549;
  content: "";
}

hr {
  margin: 24px auto;
  width: 100%;
  border-top: 2px solid #cf2a51;
}

.card_text p {
  margin: 0 0 24px;
  font-size: 14px;
  line-height: 1.5;
}

.card_text p:last-child {
  margin: 0;
}

</style>
