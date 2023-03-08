<script setup>
import DaysWrapper from './components/DaysWrapper.vue';
</script>

<template>
  <div class="wrapper">
    <DaysWrapper></DaysWrapper>
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
      DaysWrapper
    }
  }
</script>
