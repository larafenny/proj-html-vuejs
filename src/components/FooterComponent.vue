<template>
    <div class="container">
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
                <li>
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                    <a href="#">Home</a>
                </li>
                <li>
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                    <a href="#">Rates</a>
                </li>
                <li>
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                    <a href="#">Testimonials</a>
                </li>
                <li>
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                    <a href="#">Blog</a>
                </li>
                <li>
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                    <a href="#">Free Quote</a>
                </li>
            </ul>
        </div>
        <div class="last-post">
            <h2>RECENT POSTS</h2>
            <ul>
                <li>
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                    <a href="#">Heading Out To College?</a>
                </li>
                <li>
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                    <a href="#">Moving Your Business</a>
                </li>
                <li>
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                    <a href="#">Outstanding Quality</a>
                </li>
                <li>
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                    <a href="#">Cost Of Moving</a>
                </li>
                <li>
                    <font-awesome-icon icon="fa-solid fa-angle-right" />
                    <a href="#">Best Moving Tips</a>
                </li>
                
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'FooterComponent'

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";

.container{
    border-top: solid 10px $lima;
    padding: 50px 10%;
    height: 400px;
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