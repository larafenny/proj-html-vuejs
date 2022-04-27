<template>
    <div class="top-header">
        <div class="container">
            <div class="contact">
                <font-awesome-icon icon="fa-solid fa-phone-flip" />

                <span>Call us for a Free Quote: </span>
                <a href="tel:18005556709">1.800.555.6789</a>

        </div>
        <div class="social">
            <a href="#"><font-awesome-icon icon="fa-brands fa-facebook-f" /></a>
            <a href="#"><font-awesome-icon icon="fa-brands fa-twitter" /></a>
            <a href="#"><font-awesome-icon icon="fa-brands fa-instagram" /></a>
            <a href="#"><font-awesome-icon icon="fa-brands fa-youtube" /></a>
        </div>

        </div>
        
    </div>
</template>

<script>


export default {
    name: 'TopHeader'

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";

.top-header{
    background-color: #69bf14;
    height: 40px;
    color: $white;
    line-height: 40px;
    font-size: 12px;
    font-weight: 800;

    .container{
        display: flex;
        margin: 0 10%;
        justify-content: space-around;
        a{
            color: $white;
            text-decoration: none;
            &:active{
                color: $white;
            }
            &:visited{
                color: $white;
            }
        }
        .contact{
            .fa-phone-flip{
                margin-right: 10px;
            }
        }

        .social{
            display: flex;
            justify-content: space-around;
            align-items: center;
            .svg-inline--fa{
                margin-right: 10px;            
            }
        }   
    }
}
</style>