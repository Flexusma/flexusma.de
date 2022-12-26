<template>
  <div class="max-w-5xl px-6 md:px-12 mx-auto transition-all">
  <nav-menu></nav-menu>
  <router-view/>
    <div class="flex flex-col sm:flex-row items-center justify-center space-x-4 my-6 text-gray-500">
      <div>
        &copy; flexusma.de
      </div>
      <router-link :to="{name:'privacy'}" class="underline">
        Privacy
      </router-link>
      <router-link :to="{name:'imprint'}" class="underline">
        Imprint
      </router-link>
    </div>
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
