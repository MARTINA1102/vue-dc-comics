<template>
  <div>
    <HeaderPage/>
    <FasciaAzzurra/>
    <MainPage/>
    <FooterPage/>
  </div>
</template>

<script>
import HeaderPage from './HeaderPage.vue';
import FasciaAzzurra from './FasciaAzzurra.vue';
import MainPage from './MainPage.vue';
import FooterPage from './FooterPage.vue';

export default {
  components: { HeaderPage, FasciaAzzurra },
  comments: {
    HeaderPage,
    FasciaAzzurra,
    MainPage,
    FooterPage,
  },

};
</script>

<style>

</style>
