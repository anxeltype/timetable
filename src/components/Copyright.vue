<template>
  <p>{{ today }} © anxeltype team </p>
</template>

<script>
let today = new Date().getFullYear();

export default {
  data() {
    return { today };
  }
}
</script>

<style scoped>
p {
  margin-top: 130px;
  color: #8e8e8e;
}
</style>