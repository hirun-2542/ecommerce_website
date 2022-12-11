<script setup>
import Navbar from "./views/Navbar.vue";
import Banner from "./views/banner.vue";
import Feature from "./views/feature.vue";
import Category from "./views/Category.vue";
import Product from "./views/product.vue";
import Footer from "./views/footer.vue";
</script>

<template>
    <div class="E-commerce">
        <Navbar />
        <Banner />
        <Feature />
        <Category />
        <Product />
        <Footer />
        <router-view></router-view>
    </div>
</template>

<style>
*,
::after,
::before {
    box-sizing: border-box;
}

.E-commerce {
    font-family: "Poppins", sans-serif;
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #212529;
    text-align: left;
    background-color: #fff;
}

.container {
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
}

@media (min-width: 1200px) {
    .container {
        max-width: 1140px;
    }
}
</style>
