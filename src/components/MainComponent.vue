<template>
    <div>
        <FreeQuote />
        <AwardComponent />
    </div>
</template>

<script>
import FreeQuote from './FreeQuote.vue'
import AwardComponent from './AwardComponent.vue'

export default {
    name: 'MainComponent',
    components: {
        FreeQuote,
        AwardComponent
    }

}
</script>

<style>

</style>