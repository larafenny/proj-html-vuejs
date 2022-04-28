<template>
<div class="container">
    <div class="footer-container">
        <div class="about">
            <h2>ABOUT</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Architecto necessitatibus eum ipsum ab assumenda.</p>
            <div class="logo">
                <img src="/avada-movers-logo.png" alt="logo">
            </div>
        </div>
        <div class="footer-menu">
            <h2>AVADA MOVERS</h2>
            <ul>
                <li v-for="itemFooter in footerMenu">
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                    <a href="#">{{itemFooter}}</a>
                </li>
                
            </ul>
        </div>
        <div class="last-post">
            <h2>RECENT POSTS</h2>
            <ul>
                <li v-for="post in posts">
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                    <a href="#">{{post}}</a>
                </li>
            </ul>
        </div>
    </div>
    <BottomFooter />
</div>
    
</template>

<script>
import BottomFooter from './BottomFooter.vue'

export default {
    name: 'FooterComponent',
    components: {
        BottomFooter
    },
    data(){
        return{
            footerMenu: ['Home', 'Rates', 'Testimonials', 'Blog', 'Free Quote'],
            posts: ['Heading Out To College?', 'Moving Your Business', 'Outstanding Quality', 'Cost Of Moving', 'Best Moving Tips']
        }
    }


}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";

.footer-container{
    border-top: solid 10px $lima;
    padding: 50px 10%;
    min-height: 400px;
    display: flex;
    h2{
        color: $shark;
        font-size: 14px;
        font-weight: 900;
        padding: 20px 0;
    }
    
}
.about, .footer-menu, .last-post{
    width: 30%;
    padding: 0 25px;
}

.footer-menu, .last-post{
    width: 35%;
    padding: 0 25px;
}

ul{
    width: 60%;
    list-style: none;

    li{
        .fa-angle-right{
            font-size: 10px;
            margin-right: 5px;
        }
        a{
            text-decoration: none;
            color: $shark;
            font-size: 12px;
            font-weight: 800;
            line-height: 40px;
            &:hover{
                color: $lima;
            }
        }
    }
}

.logo{
    width: 40%;
    img{
        margin: 25px 0;
        height: 50px;

    }
}

</style>