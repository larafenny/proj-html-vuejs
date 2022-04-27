<template>
    <div class="container">
        <h2>MOVING WITHOUT THE HASSLE</h2>
        <h1>WE MAKE IT SIMPLE</h1>
        <h2>PROFESSIONAL SERVICE QUALITY AND CUSTOMER SATISFACTION</h2>
    </div>
</template>

<script>
export default {
    name: 'MarketingSlider'

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";

    .container{
        display: flex;
        justify-content: center;
        flex-direction: column;
        height: 320px;
        h2{
            font-size: 14px;
            color: $gray;
            font-weight: 900;
        }
        h1{
            font-size: 44px;
            color: $shark;
            font-weight: 900;
        }
    }

</style>>