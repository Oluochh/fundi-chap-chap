<script setup>
import { ref } from 'vue'
import Desktopnav from '../components/Desktopnav.vue';
import SimpleNav from '../components/simpleNav.vue';
import Mobilenav from '@/components/Mobilenav.vue';

const title = ref('Settings');
</script>
<template>
<div class="settings-container">
    <SimpleNav :title="title"  class="nav-simp"/>
    <Desktopnav class="desk-simp"/>
    
</div>
<Mobilenav/>
</template>
<style>
@import "@/style/settings.css";
</style>