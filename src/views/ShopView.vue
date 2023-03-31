<script setup>
import Panel from '../components/panel.vue';
import Searchbar from '../components/searchbar.vue';
import Categories from '../components/categories.vue';
import trendingCard from '../components/trendingCard.vue';
import popularCard from '../components/popularCard.vue';

</script>
<template>
<div class="shop-container">
    <div class="shop-s">
        <Searchbar />
    </div>
    <Panel>
    </Panel>
    <div class="categories-inner">
        <h1>categories</h1>
        <Categories/>
    </div>
    <trendingCard/>
    <popularCard/>
</div>
</template>
<style>
@import "@/style/shop.css";
</style>