<template>
  <div id="app">
    <TopHeader />
    <SliderComponent />
    <MainComponent />
    <FooterComponent />
  </div>
</template>

<script>
import TopHeader from './components/TopHeader.vue'
import SliderComponent from './components/SliderComponent.vue'
import MainComponent from './components/MainComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    TopHeader,
    SliderComponent,
    MainComponent,
    FooterComponent
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
}
</style>
