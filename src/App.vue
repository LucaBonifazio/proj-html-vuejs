<template>
  <div>
    <HeaderPage />
    <MainPage />
    <FooterPage />
  </div>
</template>

<script>
import HeaderPage from './components/HeaderPage.vue';
import MainPage from './components/MainPage.vue';
import FooterPage from './components/FooterPage.vue';

export default {
  name: 'App',
  components: {
    HeaderPage,
    MainPage,
    FooterPage,
  },
};
</script>

<style lang="scss">
  @import "~bootstrap/scss/bootstrap";
  @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,400;0,700;1,900&display=swap');

  html {
    font-family: 'Roboto', sans-serif;
  }

  .fa-solid.fa-play{
  color: rgb(0, 174, 255);
  background-color: rgb(243, 243, 243);
  padding: 1.5em;
  border: 1px solid rgba(0, 0, 0, 0.24);;
  border-radius: 10rem;
  &:hover {
    cursor: pointer;
    color: rgb(243, 243, 243);
    background-color: rgb(0, 174, 255);
  }
  }
</style>
