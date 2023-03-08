<script setup>
import TimerSandEmptyIcon from "vue-material-design-icons/TimerSandEmpty.vue";
</script>

<template>
  <div class="board">
    <div class="wrapper">
      <TimerSandEmptyIcon :size="186" fillColor="#ADADAD"></TimerSandEmptyIcon>
      <p>#ThisIsJustTheBeginning</p>
    </div>
  </div>
</template>

<script>
  export default {
    components: {TimerSandEmptyIcon}
  }
</script>

<style scoped>
.wrapper {
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
p {
  font-size: 20px;
  color:#999;
  margin-top: 70px;
}

.board {
  width: 885px;
  height: 466px;
  border: 0.5px solid rgba(0, 0, 0, 0.2);
}

</style>