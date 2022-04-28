<template>
    <div>
        <FreeQuote />
        <AwardComponent />
        <ServiceSolution />
        <MoveComponent />
    </div>
</template>

<script>
import FreeQuote from './FreeQuote.vue'
import AwardComponent from './AwardComponent.vue'
import ServiceSolution from './ServiceSolution.vue'
import MoveComponent from './MoveComponent.vue'


export default {
    name: 'MainComponent',
    components: {
        FreeQuote,
        AwardComponent,
        ServiceSolution,
        MoveComponent
    }

}
</script>

<style>

</style>