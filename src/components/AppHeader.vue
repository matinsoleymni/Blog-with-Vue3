<template>
    <header class="d-flex j-evenly align-item-c">
        <div class="right">
            <img src="../assets/logo.png" alt="Logo">
        </div>
        <div class="left">
            <ul class="d-flex list-n">
                <li><router-link to="/">Home</router-link></li>
                <li><router-link to="/blog">Blog</router-link></li>
                <li><router-link to="/about">AboutUs</router-link></li>
            </ul>
        </div>
    </header>
</template>

<script>
    export default {}
</script>

<style lang="scss">
    header{
        background-color: antiquewhite;
        border-radius: 0px 0px 30px 30px;
        margin-bottom: 50px;
        .right {
            img {
                width: 75px;
                transform: rotate(180deg);
                transition: all .5s;
                
                &:hover {
                    transition: all .5s;
                    transform: rotate(0deg);
                }
            }
        }
        .left {
            ul {
                gap: 25px;
                li {
                    font-size: 24px;
                }
                &hover {
                    transform: rotate(15deg);
                }
            }
        }

        a {
            color: rgb(98, 226, 98);
            text-decoration: none;
        }

        .router-link-active{
            color: red !important;
        }
    }
</style>