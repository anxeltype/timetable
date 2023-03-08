<template>
  <div class="days-wrapper">
    <div class="day-item-wrapper" v-for="day in days" v-bind:key="day">
      <h4>
        {{ day }}
      </h4>
    </div>
  </div>
</template>

<script>
  export default {
    data (){
      return {
        days: ["Понеділок", "Вівторок", "Середа", "Четвер", "П'ятниця"]
      }
    }
  }
</script>

<style scoped>
.days-wrapper {
  display: flex;
  flex-direction: row;
}

.day-item-wrapper:first-child {
  border-radius: 10px 0px 0px 0px;
}

.day-item-wrapper:last-child {
  border-radius: 0px 10px 0px 0px;
}
.day-item-wrapper {
  height: 63px;
  width: 177px;
  border: 0.5px solid rgba(0, 0, 0, 0.2);

  display: flex;
  align-items: center;
  justify-content: center;

  background-color: #F1F1F1;
}

.day-item-wrapper:hover {
  background-color: #e4e4e4;
}

h4 {
  font-size: 20px;
}
</style>