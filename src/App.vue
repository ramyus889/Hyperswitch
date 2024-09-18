<script setup>
import UseFlexLogo from './components/UseFlexLogo.vue';
import UseHeader from './components/UseHeader.vue';
import UseMain from './components/UseMain.vue';
</script>

<template>
  <div class="">
    <UseHeader />
    <div class="mb-20">
      <UseMain />
      <div class="flex place-content-center">
        <UseFlexLogo />
      </div>
    </div>
  </div>
</template>
