<script setup lang="ts">
import SearchPanel from '@/components/SearchPanel/SearchPanel.vue'
import MainInfo from '@/components/MainInfo/MainInfo.vue'
import TodayOverview from '@/components/TodayOverview/TodayOverview.vue'
import TodayParameters from '@/components/TodayParameters/TodayParameters.vue'

</script>

<template>
  <aside class="aside">
    <SearchPanel></SearchPanel>
    <MainInfo></MainInfo>
    <TodayOverview></TodayOverview>
    <TodayParameters></TodayParameters>
  </aside>
</template>

<style scoped>

</style>
