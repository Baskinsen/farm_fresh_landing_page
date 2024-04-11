<script setup>
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
</script>

<template>
  <Header />
  <main>
    <Hero />
  </main>
</template>

<style>
button {
  padding: 10px 30px;
  background-color: #008000;
  border: none;
  color: #ffffff;
  font-size: 18px;
  border-radius: 5px;
}

button a {
  color: #ffffff;
  text-decoration: none;
}
</style>
