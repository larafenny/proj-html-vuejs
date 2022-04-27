<template>
    <div class="container">
        <HeaderComponent />
      
  </div>
</template>

<script>
import HeaderComponent from '@/components/HeaderComponent.vue'

export default {
  name: 'SliderComponent',
  components: {
    HeaderComponent
  }
}
</script>

<style lang="scss" scoped>
    .container{
        display: flex;
        background-image: url("/src/images/avada-movers-homeherobackground-final.jpg");
        background-position: center;
        background-size: cover;
        height: 400px;

    }
</style>>