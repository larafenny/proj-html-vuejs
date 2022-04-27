<template>
    <div class="slider-container">
        <HeaderComponent />
        <MarketingSlider />
      
  </div>
</template>

<script>
import HeaderComponent from '@/components/HeaderComponent.vue'
import MarketingSlider from '@/components/MarketingSlider.vue'

export default {
  name: 'SliderComponent',
  components: {
    HeaderComponent,
    MarketingSlider
  }
}
</script>

<style lang="scss" scoped>
    .slider-container{
        display: flex;
        background-image: url("/src/images/avada-movers-homeherobackground-final.jpg");
        background-position: center;
        background-size: cover;
        height: 400px;
        background-repeat: no-repeat;
        width: 100vw;

    }
</style>>