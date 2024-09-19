<script setup>
import UseDeliver from './components/UseDeliver.vue';
import UseFlexLogo from './components/UseFlexLogo.vue';
import UseHeader from './components/UseHeader.vue';
import UseImprove from './components/UseImprove.vue';
import UseMain from './components/UseMain.vue';
import UsePayment from './components/UsePayment.vue';
import UseProductSuite from './components/UseProductSuite.vue';
import UseReduce from './components/UseReduce.vue';
import UseSeamless from './components/UseSeamless.vue';
import UseSystem from './components/UseSystem.vue';
</script>

<template>
  <div class="">
    <UseHeader />
    <div class="mb-20 flex place-content-center">
      <div class="max-w-[1440px]">
        <UseMain />
        <UseFlexLogo />
        <UsePayment />
        <UseImprove />
        <UseReduce />
        <UseSystem />
        <UseSeamless />
        <UseProductSuite />
        <UseDeliver />
      </div>
    </div>
  </div>
</template>
