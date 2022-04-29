<template>
    <div class="card-container">
        <div class="card">
            <img src="@/images/avada-movers-homeherobackground-final.jpg" alt="">
        </div>
        <div class="card">card</div>
        <div class="card">card</div>
    </div>
     
    
</template>

<script>
export default {
    name: 'ServiceCard',
    props: {
        service: Object,
    }

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";
@import "../assets/elements.scss";

    .card-container{
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 0 10%;
        width: 100%;
    

        .card{
            background-color: $lightGray;
            height: 400px;
            margin: 20px;
            width: calc(100% / 3);
            img{
                width: 100%;
            }
        }
    }

    

</style>

