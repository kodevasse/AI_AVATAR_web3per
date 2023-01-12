<script setup>
import { RouterLink, RouterView } from "vue-router";

document.documentElement.classList.add("dark");
</script>

<template>
  <!-- <header>
    <div class="container">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header> -->

  <RouterView />
</template>

<style>
body {
  background-color: rgba(0, 0, 0, 0.95);
}
</style>
