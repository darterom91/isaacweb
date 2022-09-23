<template>
  <div id="app">
    <Header class="sticky-top" />
    <Section />
    <Footer class="bg-dark text-light p-5" />
  </div>
</template>

<script>
import Header from '@/components/header_isw/Header.vue';
import Section from '@/components/sections_isw/Section.vue'
import Footer from '@/components/footer_isw/Footer.vue';

export default {
  components: {
    Header,
    Section,
    Footer
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>