<script setup>
import Card from './Card.vue'
const onClickAdd = () => {
  alert('romanelox')
}
</script>
<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      imageUrl="/sneakers/sneakers-1.jpg"
      title="Мужские кроссовки Nike Blazzer Mid Suede"
      :price="1600"
      :isAdded="true"
      :isFavorite="true"
      :onClickAdd="onClickAdd"
    />
  </div>
</template>
