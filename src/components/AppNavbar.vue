<template>
  <nav class="bg-orange text-teal rounded-b-lg shadow-md">
    <div class="container mx-auto px-4 py-4 flex justify-between items-center">
      <router-link to="/" class="flex items-center">
        <img src="@/assets/logo.png" alt="Community Center" class="logo">
      </router-link>
      <div class="hidden md:flex space-x-4">
        <router-link to="/" class="nav-link">Home</router-link>
        <router-link to="/about" class="nav-link">About Us</router-link>
        <router-link to="/events" class="nav-link">Events</router-link>
        <router-link to="/contact" class="nav-link">Contact Us</router-link>
      </div>
      <div class="flex space-x-4">
        <a href="https://www.facebook.com/profile.php?id=61552774406949" target="_blank" class="nav-link">
          <font-awesome-icon :icon="['fab', 'facebook']" />
        </a>
        <a href="https://www.instagram.com" target="_blank" class="nav-link">
          <font-awesome-icon :icon="['fab', 'instagram']" />
        </a>
        <a href="https://www.twitter.com" target="_blank" class="nav-link">
          <font-awesome-icon :icon="['fab', 'twitter']" />
        </a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'AppNavbar'
};
</script>

<style scoped>
.bg-orange {
  background-color: #ED8F79;
}
.text-teal {
  color: #127086;
}
.logo {
  height: 128px; /* Height set to 128px */
  width: 128px; /* Width set to 128px */
  transition: height 0.3s, width 0.3s;
}
.nav-link {
  color: #127086;
  text-decoration: none;
  font-size: 1.5rem; /* Font size set to 1.5rem */
}
.nav-link:hover {
  text-decoration: underline;
}
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 0; /* Increase the padding to make the navbar bigger */
}
</style>
