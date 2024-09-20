<template>
  <div id="app">
    <header class="header">
      <h1>Welcome to My Vue Page</h1>
    </header>
    <main class="main-content">
      <section class="section">
        <h2>About Us</h2>
        <img src="./assets/chop.jpg" alt="About Us" class="image" />
        <p>This is a simple one-page website built with Vue 2.</p>
      </section>
      <section class="section">
        <h2>Services</h2>
        <img src="./assets/zoro.jpg" alt="Our Services" class="image" />
        <p>We offer various services including web development, design, and consulting.</p>
      </section>
      <section class="section">
        <h2>Contact</h2>
        <img src="./assets/zoro1.jpg" alt="Contact Us" class="image" />
        <p>If you have any questions, feel free to reach out!</p>
      </section>
    </main>
    <footer class="footer">
      <p>&copy; 2024 My Vue Page</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
#app {
  text-align: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  color: #2c3e50;
  margin-top: 60px;
}

.header {
  background-color: #42b983;
  padding: 20px;
  color: white;
}

.main-content {
  padding: 20px;
}

.section {
  margin: 20px 0;
  padding: 20px;
  border: 1px solid #ddd;
  border-radius: 5px;
  background-color: #f9f9f9;
}

.image {
  max-width: 100%;
  height: auto;
  border-radius: 5px;
  margin: 10px 0;
}

.footer {
  background-color: #42b983;
  padding: 10px;
  color: white;
  position: relative;
  bottom: 0;
  width: 100%;
}
</style>
