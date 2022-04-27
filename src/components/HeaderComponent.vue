<template>
    <div class="header-container">
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
    .header-container{
        display: flex;
                width: 100vw;

        margin: 10px 10%;
        .logo{
            width: 40%;
            img{
                max-width: 150px;

            }
        }
    }
    
</style>>

