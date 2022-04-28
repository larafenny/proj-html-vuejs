<template>

    <a href="#">
        <div class="container">
            <font-awesome-icon icon="fa-regular fa-paper-plane" />
            <h2>GET A FREE QUOTE ONLINE NOW!</h2>
        </div>
    </a>
        
    
</template>

<script>
export default {
    name: 'FreeQuote'

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";
 
    .container{
        height: 100px;
        background-color: $denim;
        text-align: center;
        color: $white;
        display: flex;
        justify-content: center;
        align-items: center;

        h2{
            font-size: 14px;
        }
        .fa-paper-plane{
            margin-right: 10px;
        }
    }

    a{
        text-decoration: none;
    }

</style>