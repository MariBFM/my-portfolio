<script setup>
import Title from './components/Title.vue'
import Navigation from './components/Navigation.vue'
import Skills from './components/Skills.vue'
import Projects from './components/Projects.vue'
import Contact from './components/Contact.vue'
</script>

<template>
  <div class="flex">
    <Navigation />
    <div>
      <Title />
      <Skills />
      <Projects />
      <Contact />
    </div>
  </div>
</template>

<style>
#app {
  background-color: #120914;
}

</style>
