<script setup>
const items = [
  {
    id: 1,
    image: '/zurich.png'
  },
  {
    id: 2,
    image: '/amazon.png'
  },
  {
    id: 3,
    image: '/flipkart.png'
  },
  {
    id: 4,
    image: '/reloadHero.png'
  },
  {
    id: 5,
    image: '/junique.png'
  },
  {
    id: 6,
    image: '/starbucks.png'
  },
  {
    id: 7,
    image: '/getin.png'
  },
  {
    id: 8,
    image: '/twbs.png'
  },
  {
    id: 9,
    image: '/jio.png'
  },
  {
    id: 10,
    image: '/urbanclap.png'
  },
  {
    id: 11,
    image: '/gpay.png'
  },
  {
    id: 12,
    image: '/myntara.png'
  }
];
</script>
<template>
  <div class="flex place-content-center mt-[100px]">
    <div class="text-center">
      <div class="text-[#929fbe] text-[25px] font-semibold">GLOBAL BRANDS TRUST US</div>
      <marquee behavior="scroll" direction="">
        <div class="flex sm:gap-[64px] gap-[32px] mt-[64px] mb-[124px]">
          <div v-for="item in items" :key="item.id" class="">
            <img :src="item.image" alt="" class="sm:max-w-[232px] max-w-[117px]" />
          </div>
        </div>
      </marquee>
    </div>
  </div>
</template>
