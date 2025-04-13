<script>
import Navbar from "./Navbar.vue";

export default {
  name: "Page",
  components: {
    Navbar,
  },
};
</script>

<template>
  <div id="main-page" class="text-black dark:text-white">
    <Navbar/>
    <div id="home" class="flex items-center justify-center h-screen bg-white dark:bg-gray-900">
      <div class="grid grid-cols-1">
        <div>
          <p class="text-9xl font-medium">Hello!</p>
        </div>
        <div>
          <p class="inline-block animate-typewriter w-0 overflow-hidden whitespace-nowrap border-r text-2xl">My name is Daniel.</p>
        </div>
      </div>
    </div>
  </div>
</template>
