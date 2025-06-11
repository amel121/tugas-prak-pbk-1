<!-- App.vue -->
<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="container">
    <nav class="navbar">
      <ul>
        <li><a href="#">Beranda</a></li>
        <li><a href="#">Tentang</a></li>
        <li><a href="#">Layanan</a></li>
        <li><a href="#">Galeri</a></li>
        <li><a href="#">Kontak</a></li>
      </ul>
    </nav>

    <HelloWorld msg="Selamat Datang di Aplikasi Vue!" />
  </div>
</template>

<style scoped>
/* Warna latar belakang dan teks */
.container {
  background-color: #1e1e2f;
  color: #ffffff;
  min-height: 100vh;
  padding: 2rem;
  text-align: center;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

/* Navigasi */
.navbar {
  background-color: #29294d;
  padding: 1rem;
  border-radius: 12px;
  margin-bottom: 2rem;
  box-shadow: 0 0 12px rgba(0, 0, 0, 0.3);
}

.navbar ul {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  padding: 0;
  margin: 0;
}

.navbar a {
  text-decoration: none;
  color: #ffffff;
  font-weight: bold;
  transition: color 0.3s ease, transform 0.2s ease;
}

.navbar a:hover {
  color: #42b883;
  transform: scale(1.05);
}
</style>
