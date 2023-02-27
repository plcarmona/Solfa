<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
      
    
    <div class="wrapper">
      <HelloWorld />

      <nav>
        <RouterLink to="/">Inicio</RouterLink>
        <RouterLink to="/about">Misión y visión</RouterLink>
        <RouterLink to="/hello">Nosotros</RouterLink>
      </nav>
   

    </div>
  </header>

  <RouterView />
</template>

<style scoped>
div {
    margin-left: 2vh;
    justify-content: center;
}

header {
  line-height: 1.5;
  max-height: 100vh;
}


nav {


    
    align-items: center;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  border-left: 2px solid var(--color-border);
  margin-left: 8vh;
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
