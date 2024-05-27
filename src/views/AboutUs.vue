<template>
  <div class="container mx-auto py-12 text-primary font-sans">
    <section class="py-12">
      <h1 class="text-5xl font-bold mb-6 animate-fadeIn">About Us</h1>
      <p class="max-w-3xl mx-auto mb-6 animate-fadeIn">
        The Community Center is dedicated to providing a space for local events and activities. Our mission is to foster community spirit and provide opportunities for residents to engage in various activities and events.
      </p>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 animate-slideInUp">
        <div class="team-card p-6 bg-white text-primary rounded-xl shadow-lg transition-transform transform hover:scale-105">
          <img src="https://via.placeholder.com/300" alt="Team Member" class="rounded-full mb-4">
          <h3 class="text-2xl font-bold">John Doe</h3>
          <p class="text-secondary">Position</p>
        </div>
        <div class="team-card p-6 bg-white text-primary rounded-xl shadow-lg transition-transform transform hover:scale-105">
          <img src="https://via.placeholder.com/300" alt="Team Member" class="rounded-full mb-4">
          <h3 class="text-2xl font-bold">Jane Smith</h3>
          <p class="text-secondary">Position</p>
        </div>
        <div class="team-card p-6 bg-white text-primary rounded-xl shadow-lg transition-transform transform hover:scale-105">
          <img src="https://via.placeholder.com/300" alt="Team Member" class="rounded-full mb-4">
          <h3 class="text-2xl font-bold">Bob Johnson</h3>
          <p class="text-secondary">Position</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'AboutUs'
};
</script>

<style scoped>
@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

@keyframes slideInUp {
  from {
    transform: translateY(100%);
    opacity: 0;
  }
  to {
    transform: translateY(0);
    opacity: 1;
  }
}

.animate-fadeIn {
  animation: fadeIn 1s ease-in-out;
}

.animate-slideInUp {
  animation: slideInUp 1s ease-in-out;
}

.text-primary {
  color: #333;
}

.text-secondary {
  color: #555;
}
</style>
