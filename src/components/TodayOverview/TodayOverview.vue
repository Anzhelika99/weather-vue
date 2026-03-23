<script setup lang="ts">

</script>

<template>
  <ul class="today-overview">
    <li class="today-overview__item">
      <img src="/images/icons/rain.svg" alt="">
      <p class="today-overview__item-text">
        Немного дождливо
      </p>
    </li>
    <li class="today-overview__item">
      <img src="/images/icons/min-temp.svg" alt="">
      <p class="today-overview__item-text">
        Минимальная температура: 28°C
      </p>
    </li>
    <li class="today-overview__item">
      <img src="/images/icons/max-temp.svg" alt="">
      <p class="today-overview__item-text">
        Максимальная температура: 28°C
      </p>
    </li>
  </ul>
</template>

<style scoped>
  .today-overview {
    display: flex;
    flex-direction: column;
    gap: 6px;
  }
  .today-overview__item {
    display: flex;
    align-items: center;
    gap: 10px;
    font-size: 17px;
  }
</style>
