<script setup>
import { RouterView } from 'vue-router'
import Mobilenav from './components/Mobilenav.vue'
</script>
<template>
  <div class="app-x">
    <RouterView />
  </div>
  <Mobilenav />
</template>
<style>
@import './style/app.css';
</style>
