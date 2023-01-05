<template>
  <div class="outer__container">
    <div class="image__container"></div>
  </div>
</template>

<style scoped>
.outer__container {
  height: 25rem;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.image__container {
  width: 22.5rem;
  height: 22.5rem;
  border-radius: 1rem;
  background-image: url('../assets/image-qr-code.png');
  background-size: cover;
}
</style>
