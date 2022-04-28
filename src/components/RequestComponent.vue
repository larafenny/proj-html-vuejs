<template>
    <div class="container">
        <div class="title">Request A Free Quote</div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus soluta nemo reiciendis, adipisci amet natus fugit excepturi obcaecati tenetur eos voluptas similique, ipsum harum.</p>
        <button>CLICK HERE</button>
    </div>
</template>

<script>
export default {
    NAME: 'RequestComponent'

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";
@import "../assets/elements.scss";

.container{
    background-image: url("/src/images/avada-movers-request-quote-background.jpg");
    background-position: center;
    background-size: cover;
    height: 400px;
    background-repeat: no-repeat;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

</style>