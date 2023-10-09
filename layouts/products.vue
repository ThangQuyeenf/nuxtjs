<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4">
                <NuxtLink to="/products" class="font-bold">Productions sju</NuxtLink>
            </nav>

        </header>
        <div class="container mx-auto p-4">
            <slot />
        </div>

        <footer class="container mx-auto p-4 flex border-t-2 justify-between">

            <ul class="flex gap-4">
                <li>
                    <NuxtLink to="/" class="btn">Home</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/about" class="btn">About</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/products" class="btn">Products</NuxtLink>
                </li>
            </ul>

        </footer>
    </div>
</template>

<script setup>

</script>

<style  scoped>.router-link-exact-active {
    color: #F5E8B7;
}</style>
