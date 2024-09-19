<script setup>
import UseDeliver from './components/UseDeliver.vue';
import UseFlexLogo from './components/UseFlexLogo.vue';
import UseFooter from './components/UseFooter.vue';
import UseHeader from './components/UseHeader.vue';
import UseHyper from './components/UseHyper.vue';
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
    <div class="flex place-content-center">
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
        <UseHyper />
      </div>
    </div>
    <div class="">
      <UseFooter />
    </div>
  </div>
</template>
