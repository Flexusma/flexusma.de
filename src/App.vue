<template>
  <div class="max-w-5xl px-6 md:px-12 mx-auto transition-all">
  <nav-menu></nav-menu>
  <router-view/>
  </div>
</template>

<style>
@tailwind base;
@tailwind components;
@tailwind utilities;

</style>
<script>
import NavMenu from "@/components/Nav";
export default {
  components: {NavMenu}
}
</script>
