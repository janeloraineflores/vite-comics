<script>
  import HeaderComponent from './components/HeaderComponent.vue';
  import MainComponent from './components/MainComponent.vue'
  import FooterComponent from './components/FooterComponent.vue'

  export default {
    name: "App",
    components: {
      HeaderComponent,
      MainComponent,
      FooterComponent,
    },
    data() {
      return {};
    },
    methods: {},
  };
</script>

<template>
    
  <HeaderComponent />

  <MainComponent />
  
  <FooterComponent />


  

</template>

<style lang="scss">

  @use "assets/scss/main.scss";

  *{
    margin: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;   

    &:not(ul) {
      padding: 0;
    }
  }

  .container {
    margin: 0 auto;
    max-width: 1000px;
  }
  

</style>
