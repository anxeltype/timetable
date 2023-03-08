<script setup>
import DaysWrapper from './components/DaysWrapper.vue'
import Cont from './components/Cont.vue'
import Copyright from './components/Copyright.vue';
</script>

<template>
  <div class="wrapper">
    <DaysWrapper />
    <Cont />
    <Copyright />
  </div>
</template>

<style scoped>
.wrapper {
  background-color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  height: 100%;
}
</style>

<script>
export default {
  components: {
    DaysWrapper,
    Cont,
    Copyright
  }
}
</script>
