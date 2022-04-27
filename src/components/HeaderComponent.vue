<template>
    <div class="container">
        <div class="logo">
            <img src="/avada-movers-logo.png" alt="logo">
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

<style lang="scss" scoped>
    
</style>>

