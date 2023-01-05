<template>
  <main-container></main-container>
  <attribution-container></attribution-container>
</template>

<script>
import MainContainer from './components/MainContainer.vue';
import AttributionContainer from './components/AttributionContainer.vue';

export default {
  components: {
    MainContainer,
    AttributionContainer,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Outfit&display=swap');

* {
  box-sizing: border-box;
  font-family: 'Outfit', sans-serif;
}

body {
  margin: 0;
  background-color: hsl(212, 45%, 89%);
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
