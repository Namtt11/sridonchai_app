<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
 <div id="app">
    <router-view />
  </div>
</template>

<router-link
to="/link"
class="block ml-4 mt-4
lg:inline-block lg:mt-0 text-blue-200
hover:text-white"
>LoginItem</router-link>
