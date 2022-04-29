<template>
    <div class="card-container">
        <div class="card" >
            <img :src="service.image" alt="">
            <div class="info-container">
                <h1>{{service.title}}</h1>
                <p>{{service.description}}</p>
                <button>READ MORE</button>
            </div>
                
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
        width: 100%;
        text-align: center;
    

        .card{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background-color: $lightGray;
            width: 300px;
            img{
                width: 100%;
            }
            .info-container{
                background-color: $white;
                padding: 20px;
                margin:  20px;
                h1{
                    color: $denim;
                    font-size: 20px;
                    font-weight: 900;
                }
                p{
                    color: $shark;
                    font-size: 12px;
                    line-height: 1.8em;
                    padding: 20px 0;
                }
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

