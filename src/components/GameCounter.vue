<script setup></script>

<template>
  <div class="counter-game">
    <span class="number">0</span>

    <div class="button-group">
      <button>+</button>

      <button>-</button>
    </div>
  </div>
</template>

<style scoped>
.counter-game {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
}
.number {
  font-size: 5rem;
  font-weight: bold;
  color: white;
}
</style>
