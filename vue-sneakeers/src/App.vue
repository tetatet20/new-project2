<script setup>
import CardList from './components/CardList.vue'
import Drawer from './components/Drawer.vue'
import Header from './components/Header.vue'
</script>
<template>
  <div class="bg-white w-4/5 m-auto rounded-xl shadow-xl mt-14">
    <Drawer />
    <Header />
    <div class="p-10">
      <h2 class="text-3xl font-bold mb-8">Все кроссовки</h2>
    </div>
    <CardList />
    <h1>romeeanelox</h1>
  </div>
</template>
