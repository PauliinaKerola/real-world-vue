<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div id="layout">
  <header>

    <div class="wrapper">

      <nav>
        <RouterLink to="/">Events</RouterLink> | 
        <RouterLink to="/about">About</RouterLink>
        
      </nav>
    </div>
  </header>
  <RouterView />
  </div>
</template>

<style>
#layout
{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color:#2c3e50
}
header {
  line-height: 1.5;
  max-height: 100vh;
}


nav {
padding: 20px;
}

nav a {
  font-weight: bold;
  color:#2c3e50
}

nav a.router-link-exact-active {
  color: #42b983
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}


h2{
  font-size: 20;
  color:blueviolet
}
</style>
