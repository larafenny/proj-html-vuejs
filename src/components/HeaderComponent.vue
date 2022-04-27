<template>
    <div class="container">
        <div class="logo">
        </div>
        <MenuComponent />   
    </div>
</template>

<script>
import MenuComponent from '@/components/MenuComponent.vue'

export default {
    name: 'HeaderComponent',
    components: {
        MenuComponent
    }
}
</script>

<style>

</style>