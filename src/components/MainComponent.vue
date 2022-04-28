<template>
    <div>
        <FreeQuote />
        <AwardComponent />
        <ServiceSolution />
    </div>
</template>

<script>
import FreeQuote from './FreeQuote.vue'
import AwardComponent from './AwardComponent.vue'
import ServiceSolution from './ServiceSolution.vue'

export default {
    name: 'MainComponent',
    components: {
        FreeQuote,
        AwardComponent,
        ServiceSolution
    }

}
</script>

<style>

</style>