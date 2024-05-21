<template>
    <div class="grid grid-cols-2">
        <div>
            <img :src="product.image" alt="">
        </div>

    </div>
    <h2>{{ product.title }}</h2>
    <p>{{ productCard.price }}</p>
    <h3>{{ product.description }}</h3>
</template>

<script setup>

</script>

<style scoped>

</style>