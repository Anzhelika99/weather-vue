<script setup lang="ts">

</script>

<template>
  <div class="main-info">
    <img src="/images/1.png" alt="" class="main-info__img">
    <p class="main-info__temp">30<span class="main-info__temp-degrees">°C</span></p>
    <div class="main-info__footer">
      <p class="main-info__city">Kuala Lumpur</p>
      <p class="main-info__day">Monday</p>
    </div>
  </div>
</template>

<style scoped>
  .main-info {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 18px;
  }
  .main-info__img {
    display: inline-block;
    max-width: 50%;
    object-fit: contain;
  }
  .main-info__temp {
    display: flex;
    font-weight: bold;
    font-size: 50px;
  }
  .main-info__temp-degrees {
    font-size: 30px;
  }

  .main-info__footer {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 8px;
    width: 100%;
    padding: 0 0 20px;
    border-bottom: 1px solid var(--light-green);
    font-size: 18px;
    line-height: 140%;
  }

  @media (min-width: 800px) {
    .main-info__img {
      max-width: 100%;
    }
    .main-info__temp {
      font-size: 96px;
    }
    .main-info__temp-degrees {
      font-size: 54px;
    }
    .main-info__footer {
      flex-wrap: wrap;
      flex-direction: row;
      justify-content: space-between;
      padding: 20px 0;
      font-size: 25px;
    }
  }
</style>
