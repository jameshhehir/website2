<template>
  <div class="container mx-auto py-12 text-primary font-sans">
    <section class="py-12">
      <h1 class="text-5xl font-bold mb-6 animate-fadeIn">Contact Us</h1>
      <p class="mb-6 animate-fadeIn">Sandhills Rd, Buncurrig, Ballyheigue, Co. Kerry, Ireland</p>
      <p class="mb-6 animate-fadeIn">
        <a href="mailto:info@ballyheiguecommunitycentre.ie" class="text-green-500 hover:underline">
          info@ballyheiguecommunitycentre.ie
        </a>
      </p>
      <p class="mb-6 animate-fadeIn">Tel: (066) 7133837</p>
      <div class="map-container animate-slideInUp">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2625.3838306847325!2d-9.8338019!3d52.3883774!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x485ab69a4631c2cd%3A0xe6fe6612834ded39!2sCommunity%20Centre!5e0!3m2!1sen!2sie!4v1592288263290!5m2!1sen!2sie"
          width="600"
          height="450"
          frameborder="0"
          style="border:0;"
          allowfullscreen=""
          aria-hidden="false"
          tabindex="0"
          class="rounded-lg shadow-lg"
        ></iframe>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'ContactUs'
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

.text-green-500 {
  color: #48bb78;
}

.hover\:underline:hover {
  text-decoration: underline;
}

.map-container {
  display: flex;
  justify-content: center;
  margin-top: 2rem;
}
</style>
