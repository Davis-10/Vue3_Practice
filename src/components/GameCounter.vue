<script setup>
const isActive = false
</script>

<template>
  <button>menos</button>

  <span class="counter" :class="{ 'counter--active': isActive }">contador: 0</span>

  <button>mas</button>
</template>

<style scoped>
.counter {
  font-weight: bold;
  font-size: 2rem;
}

.counter--active {
  color: green;
}

button {
  background-color: red;
}
</style>
