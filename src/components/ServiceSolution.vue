<template>
    <div class="container">
        <div class="up-title">WE ARE A PROFESSIONAL</div>
        <div class="title">Full-Service Solution</div>
        <div class="card-container">
            <ServiceCard v-for="(services, index) in services" :key="index" :service="services"/>
        </div>
        
    </div>
</template>

<script> 
import ServiceCard from './ServiceCard.vue'

export default {
    name: 'ServiceSolution',
    components: {
        ServiceCard
    }, 
    data(){
        return {
            
        };
    },
    props: {
        services: Array,
    }

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";

.container{
    margin: 50px 10%;
    align-items: center;
    min-height: 400px;
    
    .card-container{
        width: 500px;
        display: flex;
    
    }
}

.up-title{
    color: $silver;
    font-size: 12px;
    font-weight: 900;
    text-align: center;


}

.title{
    color: $lima;
    font-size: 40px;
    font-weight: 900;
    text-align: center;

}

p{
    text-align: center;
    color: $gray;
    font-size: 12px;
    margin: 20px 0;
    padding: 0 250px;
    line-height: 1.5rem;
    font-weight: 700;

}



</style>