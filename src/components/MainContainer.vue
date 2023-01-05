<template>
  <div class="main__container">
    <image-container></image-container>
    <text-container></text-container>
  </div>
</template>

<script>
import TextContainer from './TextContainer.vue';
import ImageContainer from './ImageContainer.vue';

export default {
  components: {
    TextContainer,
    ImageContainer,
  },
};
</script>

<style scoped>
.main__container {
  height: 40rem;
  width: 25rem;
  background-color: hsl(0, 0%, 100%);
  border-radius: 1rem;
}
</style>
