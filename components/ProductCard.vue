<template>
    <div>
<img :src="product.image" alt="" srcset="">
<p> {{ product.title }}</p>
<Nuxtlink :to="`/products/${product.id}`">
<p class="boton my-4">ver detalles</p>
</Nuxtlink>
    </div>
</template>

<script setup>
const { product }= defineProps (["product"])
</script>

<style scoped>
img {
    max-height: 128px;
    max-width: 70%;
    margin: auto;
}
</style>