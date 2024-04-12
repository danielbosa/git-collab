<template>
  <HeaderComponent/>
  <MainComponent/>
  <FooterComponent/>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FoooterComponent.vue';
import MainComponent from './components/MainComponent.vue';
  export default {
    name: 'App',
    components:{
      HeaderComponent,
      FooterComponent,
      MainComponent
    }
  }
</script>

<style lang="scss" scoped>

</style>