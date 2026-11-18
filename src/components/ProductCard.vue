<script setup lang="ts">
const props = defineProps<{
  name: string;
  price: number;
}>();
</script>

<template>
  <p>商品：{{ props.name }}</p>
  <p>価格：{{ props.price }}円</p>
</template>
