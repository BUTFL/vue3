<script setup>
import MyHeader from './components/MyHeader.vue'
import MyFooter from './components/MyFooter.vue'
import MyContent from './components/MyContent.vue'
import Myright from './components/Myright.vue'</script>

<template>
  <div style="position: relative">
    <MyHeader></MyHeader>
    <Myright></Myright>
    <MyContent></MyContent>
    <MyFooter style="position: absolute;bottom: -240px;width: 100%"></MyFooter>
  </div>

</template>

<style>
</style>
