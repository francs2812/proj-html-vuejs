<template>
  <header>
        <nav>
            <a href="#" class="logo">
                <img src="../assets/img/logo-img-01.png" alt="">
            </a>

            <ul>
                <li> <a href="">homes</a> </li>
                <li> <a href="">pages</a> </li>
                <li> <a href="">blog</a> </li>
                <li> <a href="">shop</a> </li>
                <li> <a href="">events</a> </li>
                <li> <a href="">elements</a> </li>
                <li> <a href=""> <i class="fas fa-search"></i> </a> </li>
                <li> <a href=""> <i class="far fa-ellipsis-v"></i> <i class="fas fa-bars"></i> </a> </li>
            </ul>

        </nav>
       <div id="shop_slide">
            <div class="row box">
                <div class="col-1 arrows">
                    <i class="fas fa-long-arrow-alt-left"></i>
                </div>
                <div class="col-10" id="slide">
                    <div id="slide">
                        <h1>OurTeam<span>.</span></h1>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Unde reprehenderit sed nostrum tenetur.</p>
                        <div class="buttons">
                            <button style="background-color: white;">read more <span>|</span> <i class="fas fa-long-arrow-alt-right"></i></button>
                            <button class="orange">purchase <span>|</span> <i class="fas fa-long-arrow-alt-right"></i></button>
                        </div>
                    </div>
                    
                </div>
                <div class="col-1 arrows">
                   <i class="fas fa-long-arrow-alt-right"></i>
                </div>
            </div>
        </div>
  </header>
</template>

<script>
export default {
    name:"Header"
}
</script>

<style lang="scss" scoped>
@import "../components/style/General";
@import '../../node_modules/fontawesome-free/css/all.css';
    header {
        height: 100vh;
        width: 100%;
        background-image: url(../assets/img/rev-slider-main-home-img-03.jpg) ;
        background-size: cover;
        padding: 20px;
        
        nav {
            display: flex;
            align-items: center;
            justify-content:space-between;

            a {
                height: 100%;

                *:active {
                    color: $orange;
                }

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
            height: 300px;

            .box {
                height: 100%;
                padding-top: 200px;
                //background-color: blue;
           
                .arrows {
                    height: 100%;
                    //background-color: chartreuse;
                    font-size: 25px;
                    color: black;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                }
                #slide {
                    padding: 10px 50px;
                    h1 {
                        font-size: 50px;
                        span {
                            color: $orange ;
                        }
                    }

                    p {
                        width: 40%;
                        color: $greyText;
                    }
                    .buttons {
                            button {
                                font-size: 12px;
                                color: #000;
                                padding: 10px 25px;
                                margin: 10px;
                                text-transform: uppercase;
                                font-family: 'Lato', sans-serif;
                                border: 0;

                                span {
                                    font-size: 20px;
                                }

                            }
                            .orange {
                                background-color: $orange;
                                color: white;
                            }
                    }
                }
             }
        }
    }

</style>

