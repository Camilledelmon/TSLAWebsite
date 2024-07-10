<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
<div id="mymenu" className="sidnav">
<div><img id="navlogo"  src="/src/images/logo.png" alt=""></img></div>
<div className="sidnav_seprator" ><hr/></div>
<div>
    <p className="sidnav_title"> <a href="/">Accueil </a></p>
    <p className="sidnav_title">L&#39association</p>
    <p  className="sidnav_section" ><a href="game">presentation</a></p>
</div>
</div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
