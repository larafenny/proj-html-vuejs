<template>
    <div class="container">
        <div class="up-title">WE ARE A PROFESSIONAL</div>
        <div class="title">Full-Service Solution</div>
        <ServiceCard :service="services"/>
    </div>
</template>

<script>
import ServiceCard from './ServiceCard.vue'
import services from '/src/assets/data/services'

export default {
    name: 'ServiceSolution',
    components: {
        ServiceCard
    }, 
    data(){
        return {services};
    },

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";
@import "../assets/elements.scss";


</style>