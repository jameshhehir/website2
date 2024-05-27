<template>
  <div class="container mx-auto py-12 text-primary font-sans">
    <section class="relative text-center h-screen bg-cover bg-center rounded-lg overflow-hidden shadow-lg" :style="backgroundImage">
      <div class="absolute inset-0 bg-black bg-opacity-50 flex flex-col justify-center items-center rounded-lg">
        <h1 class="text-5xl font-bold text-white mb-4 animate-fadeIn">Welcome to the Community Center</h1>
        <p class="text-xl text-white mb-6 animate-slideInUp">Your place for local events and activities.</p>
        <button class="bg-green-500 text-white px-6 py-3 rounded-full shadow-lg hover:bg-green-600 transition duration-300 animate-bounce">Join Us</button>
      </div>
    </section>

    <section class="py-12">
      <h2 class="text-4xl font-bold text-center mb-8 animate-fadeIn">Our Services</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 animate-slideInUp">
        <div class="service-card p-6 bg-white text-primary rounded-xl shadow-lg transition-transform transform hover:scale-105">
          <div class="mb-4">
            <img src="https://via.placeholder.com/300x200" alt="Service Image" class="rounded-xl">
          </div>
          <h3 class="text-2xl font-bold mb-2">Service 1</h3>
          <p class="text-secondary mb-4">Description of service 1.</p>
        </div>
        <div class="service-card p-6 bg-white text-primary rounded-xl shadow-lg transition-transform transform hover:scale-105">
          <div class="mb-4">
            <img src="https://via.placeholder.com/300x200" alt="Service Image" class="rounded-xl">
          </div>
          <h3 class="text-2xl font-bold mb-2">Service 2</h3>
          <p class="text-secondary mb-4">Description of service 2.</p>
        </div>
        <div class="service-card p-6 bg-white text-primary rounded-xl shadow-lg transition-transform transform hover:scale-105">
          <div class="mb-4">
            <img src="https://via.placeholder.com/300x200" alt="Service Image" class="rounded-xl">
          </div>
          <h3 class="text-2xl font-bold mb-2">Service 3</h3>
          <p class="text-secondary mb-4">Description of service 3.</p>
        </div>
      </div>
    </section>

    <section class="py-12 text-center">
      <h2 class="text-4xl font-bold mb-8 animate-fadeIn">Latest Posts</h2>
      <div class="flex justify-center animate-slideInUp">
        <iframe 
          src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61552774406949&tabs=timeline&width=500&height=600&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true&appId" 
          width="500" 
          height="600" 
          style="border:none;overflow:hidden" 
          scrolling="no" 
          frameborder="0" 
          allowfullscreen="true" 
          allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
        </iframe>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  computed: {
    backgroundImage() {
      return {
        backgroundImage: `url(${require('@/assets/bg-image.png')})`,
        backgroundSize: 'cover',
        backgroundRepeat: 'no-repeat',
        backgroundPosition: 'center',
        width: '100%',
      };
    }
  }
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

.bg-green-500 {
  background-color: #48bb78;
}

.hover\:bg-green-600:hover {
  background-color: #38a169;
}
</style>
