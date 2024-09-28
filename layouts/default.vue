<!-- layouts/default.vue -->
<template>
    <div>
      <header>
        <h1>Classic Cars of Kenya</h1>
        <nav>
          <NuxtLink to="/">Home</NuxtLink> |
          <NuxtLink to="/history">History</NuxtLink> |
          <NuxtLink to="/media-gallery">Media Gallery</NuxtLink> |
          <NuxtLink to="/user-projects">User Projects</NuxtLink> |
          <NuxtLink to="/about">About Us</NuxtLink> |
          <NuxtLink to="/contact">Contact Us</NuxtLink>
        </nav>
      </header>
      <main>
        <!-- Render the page content here -->
        <NuxtPage />
      </main>
      <footer>
        <p>© 2024 Classic Cars of Kenya. All rights reserved.</p>
      </footer>
    </div>
  </template>
  
  <style scoped>
  header {
    background-color: #333;
    color: #fff;
    padding: 10px;
  }
  
  nav a {
    color: #ff5733;
    margin: 0 10px;
    text-decoration: none;
  }
  
  footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: #fff;
  }
  </style>
  