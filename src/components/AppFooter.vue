<template>
  <footer class="bg-orange text-white py-6 rounded-t-lg shadow-md">
    <div class="container mx-auto text-center">
      <div class="flex justify-center mb-4">
        <img src="@/assets/logo1.png" alt="Logo 1" class="h-12 mx-2 rounded-full">
        <img src="@/assets/logo2.webp" alt="Logo 2" class="h-12 mx-2 rounded-full">
        <img src="@/assets/logo3.webp" alt="Logo 3" class="h-12 mx-2 rounded-full">
      </div>
      <p>&copy; 2024 Community Center</p>
      <router-link to="/privacy-policy" class="mt-2 text-sm text-gray-200 hover:underline">
        Privacy Policy
      </router-link>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'AppFooter'
};
</script>

<style scoped>
.bg-orange {
  background-color: #ED8F79;
}
.hover\:underline:hover {
  text-decoration: underline;
}
.text-gray-200 {
  color: #E5E7EB; /* A lighter shade of gray for better contrast */
}
</style>
