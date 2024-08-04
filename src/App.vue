<script setup>
import AboutUs from './components/AboutUs.vue';
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import WhyChooseUsVue from './components/WhyChooseUs.vue';
import FreshVeggies from './components/FreshVeggies.vue'
import SpecialDishes from './components/SpecialDishes.vue'
import WhatClientsHaveToSay from './components/WhatClientsHaveToSay.vue'
import Newsletter from './components/Newsletter.vue'
import Footer from './components/Footer.vue';
</script>

<template>
  <Header />
 <main>
    <Hero />
    <WhyChooseUsVue />
    <AboutUs />
    <FreshVeggies />
    <SpecialDishes />
    <WhatClientsHaveToSay />
    <Newsletter />
  </main>
    <Footer />
</template>

<style>

main {
  display: grid;
  gap: 100px;
  padding: 30px 100px;
}

button {
  padding: 15px 30px;
  background-color: #008000;
  border: none;
  color: #ffffff;
  font-size: 18px;
  border-radius: 5px;
  cursor: pointer;
}

button a {
  color: #ffffff;
  text-decoration: none;
}
</style>
