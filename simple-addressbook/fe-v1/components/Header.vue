<template>
  <header class="header">
    <div class="container">
      <div class="logo">
        <img src="/logo.png" alt="Logo">
      </div>
      <nav class="nav">
        <ul>
          <li>
            <nuxt-link to="/">Home</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/about">About</nuxt-link>
          </li>
          <!-- Add more menu items as needed -->
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  // You can define component logic here
}
</script>

<style scoped>
.header {
  background-color: #fff;
  border-bottom: 1px solid #ddd;
  padding: 10px 0;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.logo img {
  height: 40px;
  /* Adjust the size as needed */
}

.nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.nav ul li {
  display: inline-block;
  margin-right: 20px;
}

.nav ul li:last-child {
  margin-right: 0;
}

.nav ul li a {
  text-decoration: none;
  color: #333;
  transition: color 0.3s ease;
}

.nav ul li a:hover {
  color: #007bff;
}</style>
