<template>
  <section class="hero">
    <div class="hero-content">
      <h1 class="hero-title">Your Naval Industry Partner</h1>
      <p class="hero-subtitle">Providing Quality Maintenance and Repair Solutions</p>
      <a href="#contact" class="hero-button">Contact Us</a>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection',
};
</script>

<style scoped>
.hero {
  background-image: url('https://example.com/hero-background.jpg');
  background-size: cover;
  background-position: center;
  height: 400px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.hero-content {
  text-align: center;
  color: #fff;
}

.hero-title {
  font-size: 36px;
  font-weight: bold;
  margin-bottom: 20px;
}

.hero-subtitle {
  font-size: 20px;
  margin-bottom: 30px;
}

.hero-button {
  display: inline-block;
  background-color: #fff;
  color: #333;
  padding: 12px 24px;
  border-radius: 4px;
  text-decoration: none;
  font-weight: bold;
  transition: background-color 0.3s ease, color 0.3s ease;
}

.hero-button:hover {
  background-color: #333;
  color: #fff;
}
</style>

