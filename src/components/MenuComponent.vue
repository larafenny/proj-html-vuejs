<template>
    <div class="menu-container">
        <ul>
            <li v-for="item in menu"><a href="#">{{item}}</a></li>
            
        </ul>
        <button>FREE QUOTE</button>
    </div>

</template>

<script>
export default {
    name: 'MenuComponent',
    data(){
        return{
            menu: ['Home', 'Rates', 'Testimonials', 'FAQ', 'Blog', 'Contact']
        }
    },

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";
@import "../assets/elements.scss";


    .menu-container{
        width: 50%;
        display: flex;
        height: 50px;
        line-height: 50px;

        ul{
            width: 60%;
            list-style: none;
            display: flex;
            justify-content: space-around;

            li{
                a{
                    text-decoration: none;
                    color: $shark;
                    font-size: 12px;
                    font-weight: 800;
                    &:hover{
                        color: $lima;
                    }
                }
            }
        }
        
            
        
    }
    

</style>