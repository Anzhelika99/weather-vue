<script setup lang="ts">
import SearchInput from '@/components/SearchInput/SearchInput.vue'
</script>

<template>
  <form class="search" method="get" action="">
    <button class="search__button">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M16.9269 17.04L20.4 20.4M19.28 11.44C19.28 15.7699 15.7699 19.28 11.44 19.28C7.11009 19.28 3.6 15.7699 3.6 11.44C3.6 7.11009 7.11009 3.6 11.44 3.6C15.7699 3.6 19.28 7.11009 19.28 11.44Z" stroke="#7E7C7C" stroke-width="2" stroke-linecap="round" />
      </svg>
    </button>
    <SearchInput />
  </form>
</template>

<style scoped>
  .search {
    position: relative;
    background: var(--light-green);
    border-radius: 25px;
    padding: 10px 20px;
    display: flex;
    align-items: center;
    gap: 25px;
  }
  .search__button {
    display: flex;
    align-items: center;
  }
  .search__button:focus {

  }
</style>
