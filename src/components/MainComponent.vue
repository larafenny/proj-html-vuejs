<template>
    <div>
        <FreeQuote />
        <AwardComponent />
        <ServiceSolution :services="services" />
        <MoveComponent />
        <TestimonialComponent :testimonials="testimonials" />
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
import testimonials from '/src/assets/data/testimonial'


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
        return {
            services,
            testimonials
        };

    },
  

}
</script>

<style>

</style>