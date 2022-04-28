<template>
    <div class="menu-container">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Rates</a></li>
            <li><a href="#">Testimonials</a></li>
            <li><a href="#">FAQ</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
        <button>FREE QUOTE</button>
    </div>

</template>

<script>
export default {
    name: 'MenuComponent'

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