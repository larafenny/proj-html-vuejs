<template>
    <div class="header-container">
        <div class="logo">
            <img src="/avada-movers-logo.png" alt="logo">
        </div>
        <MenuComponent :mainMenu="menu"/>   
    </div>
</template>

<script>
import MenuComponent from '@/components/MenuComponent.vue'
import menu from '/src/assets/data/menu'

export default {
    name: 'HeaderComponent',
    components: {
        MenuComponent
    },
    data(){
        return {menu};
    },
}
</script>

<style lang="scss" scoped>
    .header-container{
        height: 80px;
        display: flex;
        padding: 20px 0;
        margin: 0px 10%;
        .logo{
            width: 40%;
            img{
                height: 50px;

            }
        }
    }
    
</style>>

