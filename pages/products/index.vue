<template>
    <div>
      <h1 class="text-3xl font-bold mx-10 my-10 tex text-lime-600">
      Productos
    </h1>
    <div class="grid grid-cols-4 gap-5 mx-10">

    </div>
    <div v-for="p in products"></div>
    <nuxt-link :to="products/${p.id}">{{ p.tittle }}</nuxt-link>
    </div>
  </template>

<script setup>
const {data:products} = await useFetch ('https://fakestoreapi.com/products')
</script>

<style lang="scss" scoped>

</style>