<script setup>
import DaysWrapper from './components/DaysWrapper.vue';
import Cont from "./components/Cont.vue";
</script>

<template>
  <div class="wrapper">
    <DaysWrapper></DaysWrapper>
    <Cont></Cont>
  </div>
</template>

<style scoped>
.wrapper {
  background-color: white;
}
</style>

<script>
  export default {
    components: {
      DaysWrapper,
      Cont
    }
  }