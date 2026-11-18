<script setup lang="ts">
import ProductCard from './ProductCard.vue';
const product = {
  name: 'りんご',
  price: 150,
};
</script>

<template>
  <section>
    <ProductCard :name="product.name" :price="product.price" />
  </section>
</template>
