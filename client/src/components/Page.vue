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
    <Navbar />
    <div
      id="home"
      class="flex items-center justify-center h-screen bg-white dark:bg-gray-900"
    >
    <div>
          <p
            class="inline-block animate-typewriter w-0 overflow-hidden whitespace-nowrap border-r text-9xl"
          >
            Hi, I'm Daniel.
          </p>
          <p class="text-2xl font-medium">Passionate in software engineering</p>
        </div>
    </div>
    <div
      id="about"
      class="flex items-center justify-center h-screen bg-white dark:bg-gray-900"
    >
      <p class="text-8xl font-medium">About</p>
      <p class="text-2xl font-medium">I am a software engineer with a passion for building web applications.</p>
    </div>
  </div>
</template>
