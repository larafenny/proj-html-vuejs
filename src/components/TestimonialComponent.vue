<template>
    <div class="container">
        <div class="up-title">HAPPY CUSTOMERS</div>
        <div class="title">Testimonials</div>
        <CardTestimonial v-for="(testimonials, index) in testimonials" :key="index" :testimonial="testimonials"/>
        <button>READ MORE TESTIMONIALS</button>
    </div>
</template>

<script>
import CardTestimonial from './CardTestimonial.vue'

export default {
    name: 'TestimonialComponent',
    components: {
        CardTestimonial
    },
    props: {
        testimonials: Array
    }

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";
@import "../assets/elements.scss";

.container{
    background-image: url("/src/images/avada-movers-testimonial-background.jpg");
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}
    

    

</style>