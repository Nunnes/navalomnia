<template>
  <header class="nav-menu">
    <nav class="nav-container">

      <h1 id="name-one">Naval</h1>
      <div class="logo">
        <img src="@/assets/logo.png"  alt="Naval Omni Logo">
      </div>
      <h1 id="name-two">Omni</h1>
      <ul class="nav-links">
        <li class="nav-link">
          <a href="#products">Products</a>
        </li>
        <li class="nav-link">
          <a href="#services">Services</a>
        </li>
        <li class="nav-link">
          <a href="#about">About Us</a>
        </li>
        <li class="nav-link">
          <a href="#contact">Contact</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'NavMenu',
};
</script>

<style scoped>


#name-one {
  color: #fff;
  font-size: 2rem;
  font-weight: bold;
  margin-right: 10px;
}

#name-two {
  color: #fff;
  font-size: 2rem;
  font-weight: bold;
  margin-left: 10px;
}

.nav-menu {
  background-color: #333;
  padding: 20px;
  position: fixed;
  justify-content: space-around;
  width: 100%;
  top: 0;
  left: 0;
  z-index: 999;
  display: flex;
  justify-content: center;
  align-items: center;
}

.nav-container {
  display: flex;
  
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
  width: 100%;
  padding: 0 20px;
}

.logo img {
  width: 75px;
  height: auto;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav-link a {
  text-decoration: none;
  color: #fff;
  font-weight: bold;
  transition: color 0.3s ease;
}

.nav-link a:hover {
  color: #ccc;
}
</style>
