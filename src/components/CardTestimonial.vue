<template>
    <div class="container">
        <img src="@/images/avada-movers-johndoe-final.jpg" alt="">
        <img v-bind:src="'@/images/' + testimonial.image" alt="">
        <h1>{{testimonial.name}}</h1>
        <p>{{testimonial.info}}</p>
    </div>
</template>

<script>
export default {
    name: 'CardTestimonial',
    props: {
        testimonial: Object
    }

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";

.container{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            width: 400px;
            text-align: center;
            img{
                width: 70%;
                border-radius: 50%;
                margin-bottom: 20px;

            }
            
                h1{
                    color: $denim;
                    font-size: 20px;
                    font-weight: 900;
                    margin-bottom: 20px;

                }
                p{
                    color: $shark;
                    font-size: 12px;
                    line-height: 1.8em;
                    margin-bottom: 20px;
                }
            
        }

</style>