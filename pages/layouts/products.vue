<template>
    <div>
        <header>
            <nav>
                <NuxtLink to = "/products"> NUXT DOJO Merge</NuxtLink>
            </nav>
        </header>

        <!-- output the page content-->
        <div>
            <slot />
        </div>
<!-- 
        <div>
            <footer>
            <ul>
                <li><NuxtLink to = "/">Home</NuxtLink></li>
                <li><NuxtLink to = "/about">About</NuxtLink></li>
                <li><NuxtLink to = "/products">Products</NuxtLink></li>
            </ul>
        </footer>
        </div> -->
    </div>
</template>

<style scoped>
</style>