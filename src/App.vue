<template>
  <div id="app" class="bg-background text-primary min-h-screen flex flex-col">
    <AppNavbar />
    <router-view class="flex-grow" />
    <div class="support-section py-4 bg-white shadow-md text-center">
      <div class="container mx-auto flex flex-col items-center">
        <p class="text-sm text-secondary">
          This project is supported by the Department of Rural and Community Development and Pobal through the Community Services Programme
        </p>
      </div>
    </div>
    <AppFooter />
  </div>
</template>

<script>
import AppNavbar from './components/AppNavbar.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  components: {
    AppNavbar,
    AppFooter
  }
};
</script>

<style scoped>
.bg-background {
  background-color: #f9f9f9;
}
.text-primary {
  color: #333;
}
.text-secondary {
  color: #555;
}
.min-h-screen {
  min-height: 100vh;
}
.flex-grow {
  flex-grow: 1;
}
</style>
