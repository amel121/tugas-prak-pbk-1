<!-- App.vue -->
<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank" rel="noopener noreferrer">
      <img
        src="https://vitejs.dev/logo.svg"
        class="logo"
        alt="Vite Logo"
      />
    </a>
    <a href="https://vuejs.org/" target="_blank" rel="noopener noreferrer">
      <img
        src="https://vuejs.org/images/logo.png"
        class="logo vue"
        alt="Vue Logo"
      />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms ease-in-out;
}

/* Logo Vite bersinar saat hover */
.logo:hover {
  filter: drop-shadow(0 0 12px #646cffaa);
}

/* Logo Vue bersinar saat hover */
.logo.vue:hover {
  filter: drop-shadow(0 0 12px #42b883aa);
}
</style>
