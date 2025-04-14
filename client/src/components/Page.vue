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
      class="flex flex-col items-center justify-center h-screen bg-white dark:bg-gray-900"
    >
      <p class="text-8xl font-medium">About</p>
      <p class="text-2xl font-medium">
        I am a software engineer with a passion for building web applications.
      </p>

      <div class="grid grid-cols-4">
        <div>
          <a
            href="#"
            class="block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow-sm hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700"
          >
            <h5
              class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
            >
              Java
            </h5>
            <i class="fab fa-java fa-3x"></i>
          </a>
        </div>
        <div>
          <a
            href="#"
            class="block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow-sm hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700"
          >
            <h5
              class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
            >
              JavaScript
            </h5>
            <i class="fab fa-js fa-3x"></i>
          </a>
        </div>
        <div>
          <a
            href="#"
            class="block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow-sm hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700"
          >
            <h5
              class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
            >
              CSS
            </h5>
            <i class="fab fa-css3 fa-3x"></i>
          </a>
        </div>
        <div>
          <a
            href="#"
            class="block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow-sm hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700"
          >
            <h5
              class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
            >
              HTML
            </h5>
            <i class="fab fa-html5 fa-3x"></i>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>
