<script setup>
import UseFlexLogo from './components/UseFlexLogo.vue';
import UseHeader from './components/UseHeader.vue';
import UseMain from './components/UseMain.vue';
import UsePayment from './components/UsePayment.vue';
</script>

<template>
  <div class="">
    <UseHeader />
    <div class="mb-20">
      <UseMain />
      <div class="flex place-content-center">
        <UseFlexLogo />
      </div>
      <div class="bg-black">
        <div class="flex place-content-center">
          <UsePayment />
        </div>
      </div>
    </div>
  </div>
</template>
