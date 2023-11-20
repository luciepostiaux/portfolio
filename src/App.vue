<script setup>
import { RouterView } from "vue-router";
import NavBar from "./components/NavBar.vue";

import FooterBar from "./components/FooterBar.vue";
</script>

<template>
  <header>
    <div class="">
      <NavBar />
    </div>
  </header>
  <main>
    <RouterView />
  </main>
  <footer>
    <div class="">
      <FooterBar />
    </div>
  </footer>
</template>
