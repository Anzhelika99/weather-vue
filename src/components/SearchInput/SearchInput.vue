<script setup lang="ts">
</script>

<template>
  <input class="search__input" id="search-input" type="search">
  <label class="search__label" for="search-input" aria-label="Поиск города">
    Поиск города
  </label>
</template>

<style scoped>
.search__input {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  padding: 10px 20px 10px 69px;
  font-size: 16px;
  line-height: 120%;
  color: var(--light-dark-text);
  background: transparent;
  transition: all .2s ease;
  border-radius: 25px;
  border: 2px solid transparent;
  box-sizing: border-box;
}
.search__label {
  font-size: 16px;
  line-height: 120%;
  color: var(--light-dark-text);
}
.search__input:focus {
  outline: none;
  border: 2px solid var(--white);
}
.search__input:focus + .search__label {
  display: none;
}
</style>
