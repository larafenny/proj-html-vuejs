<template>
    <div class="container">
        <div class="up-title">WE ARE A PROFESSIONAL</div>
        <div class="title">Full-Service Solution</div>
        <ServiceCard />
    </div>
</template>

<script>
import ServiceCard from './ServiceCard.vue'

export default {
    name: 'ServiceSolution',
    components: {
        ServiceCard
    }

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";
@import "../assets/elements.scss";


</style>