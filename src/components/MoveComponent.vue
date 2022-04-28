<template>
    <div class="container">
        <div class="info-box">
            <div class="up-title">WE REMOVE THE HEADACHE FROM MOVING</div>
            <div class="title">Move With Ease</div>
            <hr>
            <p>With our super simple service we can take you from getting a quote, right through to being in your new home with all of your belongings securely packed and safely delivered, even in the rooms of your choice.</p>
            <button>GET A FREE QUOTE NOW</button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'MoveComponent'

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";

.container{
    background-image: url("/src/images/avada-movers-servicetwophoto-final.jpg");
    background-position: center;
    background-size: cover;
    height: 400px;
    background-repeat: no-repeat;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

.info-box{
    border: solid 10px $darkGreen;
    width: 50%;
    color: $white;
    margin-right: 80px;
    background-color: $lima;
    padding: 20px;
    display: flex;
    flex-direction: column;
    hr{
        width: 50%;
        align-self: center;
    }
    
}


.up-title{
    font-size: 12px;
    font-weight: 900;
    text-align: center;


}

.title{
    font-size: 40px;
    font-weight: 900;
    text-align: center;

}

p{
    text-align: center;
    font-size: 12px;
    padding: 0 20px;
    line-height: 1.5rem;
    font-weight: 700;

}

button{
    align-self: center;
    height: 20px;
    border-radius: 50px;
    padding: 0px 15px;
    color: $white;
    background-color: $denim;
    border: none;
    font-size: 10px;
    font-weight: 900;
    margin: 20px 0;
    &:hover{
        cursor: pointer;
        color: $silver;
        transform: scale(1.1);
    }
}
</style>