<template>
    <div>
        <FreeQuote />
        <AwardComponent />
        <ServiceSolution :services="services" />
        <MoveComponent />
        <TestimonialComponent />
        <RequestComponent />
    </div>
</template>

<script>
import FreeQuote from './FreeQuote.vue'
import AwardComponent from './AwardComponent.vue'
import ServiceSolution from './ServiceSolution.vue'
import MoveComponent from './MoveComponent.vue'
import TestimonialComponent from './TestimonialComponent.vue'
import RequestComponent from './RequestComponent.vue'

import services from '/src/assets/data/services'



export default {
    name: 'MainComponent',
    components: {
        FreeQuote,
        AwardComponent,
        ServiceSolution,
        MoveComponent,
        TestimonialComponent,
        RequestComponent
    },
    data(){
        return {services};
    },
  

}
</script>

<style>

</style>