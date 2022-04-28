<template>
    <div>
        <FreeQuote />
        <AwardComponent />
        <ServiceSolution />
        <MoveComponent />
        <TestimonialComponent />
    </div>
</template>

<script>
import FreeQuote from './FreeQuote.vue'
import AwardComponent from './AwardComponent.vue'
import ServiceSolution from './ServiceSolution.vue'
import MoveComponent from './MoveComponent.vue'
import TestimonialComponent from './TestimonialComponent.vue'


export default {
    name: 'MainComponent',
    components: {
        FreeQuote,
        AwardComponent,
        ServiceSolution,
        MoveComponent,
        TestimonialComponent
    }

}
</script>

<style>

</style>