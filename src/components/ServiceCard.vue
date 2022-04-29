<template>
    <div class="card-container">
        <div class="card" >
            <img src="" alt="">
            <h1>{{service.title}}</h1>
            <p>{{service.description}}</p>
            <button>READ MORE</button>
        </div>
        
    </div>
     
    
</template>

<script>
export default {
    name: 'ServiceCard',
    props: {
        service: Object

    }

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";

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
            width: 300px;
            img{
                width: 100%;
            }
        }
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
        &:hover{
            cursor: pointer;
            color: $silver;
            transform: scale(1.1);
        }
}
    

</style>

