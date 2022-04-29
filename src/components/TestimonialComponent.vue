<template>
    <div class="container">
        <div class="up-title">HAPPY CUSTOMERS</div>
        <div class="title">Testimonials</div>
        <div class="testimonial-card">
            <CardTestimonial v-for="(testimonials, index) in testimonials" :key="index" :testimonial="testimonials"/>
        </div>
        
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
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}
.testimonial-card{
    display: flex;
}
    

    

</style>