<template>
    <div class="container">
        <img src="" alt="">
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
                width: 100%;
            }
            
                h1{
                    color: $denim;
                    font-size: 20px;
                    font-weight: 900;
                }
                p{
                    color: $shark;
                    font-size: 12px;
                    line-height: 1.8em;
                }
            
        }

</style>