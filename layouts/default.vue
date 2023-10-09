<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to='/' class="font-bold">Nuxt Ex App</NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/" class="btn">Home</NuxtLink></li>
                    <li><NuxtLink to="/about" class="btn">About</NuxtLink></li>
                    <li><NuxtLink to="/products" class="btn">Products</NuxtLink></li>    
                </ul>
            </nav>
        </header>
        <div class="container mx-auto p-4">
            <slot />
        </div>
        

    </div>
</template>

<script setup>

</script>

<style  scoped>
    .router-link-exact-active{
        color: #F5E8B7;
    }
</style>
