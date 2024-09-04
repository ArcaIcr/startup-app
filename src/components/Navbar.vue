<script setup>
import logo from "@/assets/img/logo.png";
</script>

<template>
  <nav class="bg-purple-700 border-b border-white-500">
    <div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
      <div class="flex h-20 items-center justify-between">
        <div
          class="flex flex-1 items-center justify-center md:items-stretch md:justify-start"
        >
          <!-- Logo -->
          <a class="flex flex-shrink-0 items-center mr-4" href="index.html">
            <img class="h-10 w-auto" :src="logo" alt="Vue Jobs" />
            <span class="hidden md:block text-white text-2xl font-bold ml-2"
              >StartUp Compass</span
            >
          </a>
          <div class="md:ml-auto">
            <div class="flex space-x-2">
              <a
                href="index.html"
                class="text-white bg-purple-700 hover:bg-violet-900 hover:text-white rounded-md px-3 py-2"
                >Home</a
              >
              <a
                href="about.html"
                class="text-white hover:bg-violet-900 hover:text-white rounded-md px-3 py-2"
                >About</a
              >
              <a
                href="pricing.html"
                class="text-white hover:bg-violet-900 hover:text-white rounded-md px-3 py-2"
                >Pricing</a
              >
              <a
                href="log-in.html"
                class="text-white hover:bg-violet-900 hover:text-white rounded-md px-3 py-2"
                >Log-in</a
              >
              <a
                href="sign-up.html"
                class="text-white hover:bg-violet-900 hover:text-white rounded-md px-3 py-2"
                >Sign-up</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>
