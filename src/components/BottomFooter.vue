<template>
    <div class="bottom-footer">
        <div class="link-element">
            <ul>
                <li>
                    <a href="#">&copy; Copyright 2012 - 2020</a>
                </li>
                <li>
                    <span class="divider"></span>

                </li>
                <li>
                    <a href="#">Avada Theme By ThemeFusion</a>
                </li>
                <li>
                    <span class="divider"></span>

                </li>
                <li>
                    <a href="#">All Rights Reserved</a>
                </li>
                <li>
                    <span class="divider"></span>

                </li>
                <li>
                    <a href="#">Powered by WordPress</a>
                </li>
            </ul>
        </div>
        <div class="social-icon">
            <a href="#"><font-awesome-icon icon="fa-brands fa-facebook-f" /></a>
            <a href="#"><font-awesome-icon icon="fa-brands fa-twitter" /></a>
            <a href="#"><font-awesome-icon icon="fa-brands fa-instagram" /></a>
            <a href="#"><font-awesome-icon icon="fa-brands fa-youtube" /></a>
        </div>
    </div>
</template>

<script>
export default {
    name: 'BottomFooter'

}
</script>

<style lang="scss" scoped>
@import "../assets/palette.scss";

.bottom-footer{
    background-color: $lima;
    height: 100px;
    color: $white;
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

}

.link-element{
    ul{
        display: flex;
        list-style: none;
        font-size: 9px;

        li{
            padding: 0 5px;
        }
    }

}

.divider{
    border-right: solid 1px $white;
    line-height: 40px;

}

a{
            color: $white;
            text-decoration: none;
            font-weight: 800;
            line-height: 40px;
            &:hover{
                color: $shark;
            }
        }

.social-icon{
    color: $white;
    a{
            margin: 0 10px;
    }
}


</style>