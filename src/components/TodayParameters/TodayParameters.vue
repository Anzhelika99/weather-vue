<script setup lang="ts">

</script>

<template>
  <ul class="today-parameters">
    <li class="today-parameters__item">
      <img src="/images/icons/humidity.svg" alt="">
      <div class="today-parameters__item-text">
        <p class="today-parameters__item-degree">83%</p>
        <p>Влажность</p>
      </div>
    </li>
    <li class="today-parameters__item">
      <img src="/images/icons/wind-speed.svg" alt="">
      <div class="today-parameters__item-text">
        <p class="today-parameters__item-degree">6km/h</p>
        <p>Скорость ветра</p>
      </div>
    </li>
  </ul>
</template>

<style scoped>
.today-parameters {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 16px;
  border: 1px solid rgba(0, 0, 0, 0.1);
  box-shadow: 2px 4px 5px 0 rgba(0, 0, 0, 0.25);
  background: rgba(37, 34, 34, 0.65);
  border-radius: 12px;
  padding: 15px;
}
.today-parameters__item {
  display: flex;
  align-items: center;
  gap: 8px;
  font-size: 16px;
  font-weight: 500;
}
.today-parameters__item-degree {
  font-weight: 700;
  font-size: 24px;
}
</style>
