<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam beatae eaque excepturi totam inventore, ratione est dolor ullam atque voluptatum!</p>
  </div>
</template>

<script setup>
  const { id } = useRoute().params
</script>

<style scoped>

</style>