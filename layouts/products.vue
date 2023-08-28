<template>
    <header>
        <nav>
            <NuxtLink to="/products">Blog Merch</NuxtLink>
        </nav>
    </header>

    <!-- output the page content -->
    <div>
        <slot />
    </div>

    <footer>
        <ul>
            <li><NuxtLink to="/">Home</NuxtLink></li>
            <li><NuxtLink to="/about">About</NuxtLink></li>
            <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
    </footer>
</template>

<style scoped>
.router-link-exact-active{
    color: rgb(37, 175, 37);
}

</style>