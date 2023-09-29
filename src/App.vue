<script setup>
import NavMenu from '@/components/NavMenu.vue'
import Navbar from './components/Navbar.vue'
</script>

<template>
  <Navbar />
  <h1 class=" text-red-500">The main companies Directory</h1>
  <NavMenu />
  <RouterView />
</template>
