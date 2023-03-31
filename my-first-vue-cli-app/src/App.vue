<script>
import HomeLink from './components/HomeLink.vue'
import NavLink from './components/NavLink.vue'
export default {
  name: 'App',
  components: {
    HomeLink,
    NavLink
  }
}
</script>

<template>
  <div id="app">
    <nav>
      <NavLink url="/" text="Accueil" />
      <NavLink url="/about" text="A propos" />
    </nav>
    <p>Bienvenue sur notre page d'<HomeLink /></p>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
