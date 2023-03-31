<script setup>
import Panel from '../components/panel.vue';
import Categories from '../components/categories.vue';
import Searchbar from '../components/searchbar.vue';

</script>
<template>
<div class="shop-container">
    <Searchbar/>
    <Panel>
    </Panel>
    <div class="categories-inner">
        <h1>categories</h1>
        <Categories/>
    </div>
</div>
</template>
<style>
@import "@/style/shop.css";
</style>