<template>
<div class="py-1 flex items-center text-gray-500 space-x-8 font-semibold">
  <div class="flex items-center">
    <img class="h-10" src="../assets/logo.png" alt="logo">
    <div class="text-gray-800">flexusma</div>
  </div>
  <div class="flex-grow"></div>
  <router-link :to="{name:'home'}" class="cursor-pointer text-gray-800">
    Home
  </router-link>
  <a href="/#projects" class="cursor-pointer">
    Projects
  </a>
  <a href="/#contact" class="cursor-pointer pr-4">
    Contact
  </a>
</div>
</template>

<script>
export default {
  name: "Nav-Menu"
}
</script>

<style scoped>

</style>
