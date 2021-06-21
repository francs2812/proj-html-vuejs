<template>
  <header>
        <nav>
            <a href="#" class="logo">
                <img src="../assets/img/logo-img-01.png" alt="">
            </a>

            <ul>
                <li><a href="">homes</a></li>
                <li><a href="">pages</a></li>
                <li><a href="">blog</a></li>
                <li><a href="">shop</a></li>
                <li><a href="">events</a></li>
                <li><a href="">elements</a></li>
                <li><a href="">serch</a></li>
                <li><a href="">menu</a></li>
            </ul>

        </nav>
        <div id="shop_slide">
            <div></div>
        </div>
  </header>
</template>

<script>
export default {
    name:"Header"
}
</script>

<style lang="scss" scoped>
    header {
        height: 100vh;
        width: 100%;
        background-image: url(../assets/img/rev-slider-main-home-img-03.jpg);
        background-size: cover;
        padding: 20px;
        
        nav {
            display: flex;
            align-items: center;
            justify-content:space-between;

            a {
                height: 100%;

                img {
                   height: 100%; 
                }
            }

            ul {
                li {
                    display: inline-block;
                    margin: 10px;

                    a {
                        text-decoration: none;
                        color: black;
                        text-transform: uppercase;
                        font-family: 'Lato', sans-serif;
                        font-weight: 700;
                    }

                }
            }

        }
        #shop_slide {
            background-color: blue;
            div {
                display: block;
                height: 300px;
            }
        }
    }

</style>

