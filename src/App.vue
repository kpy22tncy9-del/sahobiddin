<template>
  <div class="glass">
    <h1>Hello, Glassmorphism!</h1>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style scoped>
.glass {
  background: rgba(255, 255, 255, 0.1);
  border-radius: 15px;
  backdrop-filter: blur(10px);
  box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
  padding: 20px;
  color: white;
}
</style>