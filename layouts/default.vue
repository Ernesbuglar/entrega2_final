<template>
    <div>
        <header class="flex justify-between mx-10 my-10">
         <div>logo</div>

         <div class="flex gap-7 text-white">
            <div class="pesto"><button><NuxtLink to="/">home</NuxtLink></button></div>
            <div class="pesto"><button><NuxtLink to="/about">about</NuxtLink></button></div>
            <div class="pesto"><button><NuxtLink to="/products">products</NuxtLink></button></div>
            
         </div>
    >
</header>
    </div>
    <div>
        <slot 7></slot>
    </div>
</template>