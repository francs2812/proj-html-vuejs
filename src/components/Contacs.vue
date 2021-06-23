<template>
    <div id="box">
        <div class=" map">
            <div id="immage1">
                <img  src="../assets/img/h1-contact-rev-02.png" alt="X">
                <h1>
                    New York Coaching
                    <p>read more</p>
                </h1>
            </div>

            <div id="immage2">
                <img src="../assets/img/h1-contact-rev-02.png" alt="X">
            </div>

            <div id="immage3">
                <img src="../assets/img/h1-contact-rev-02.png" alt="X">

            </div>
            
        </div>
        <div class=" contact">
            <h1>Contact us <span class="orange-class">.</span></h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <div class="line-space"></div>
            <form action="/action_page.php">
                <input placeholder="Your Name" type="text" id="name" name="name">
                <input placeholder="Your Email" type="email" id="email" name="email">
                <input placeholder="Write a message ..." type="textarea" id="textarea" name="textarea">
                <a id="button" type="submit" href="">send  
                    |   <i class="fas fa-long-arrow-alt-right"> </i>
                </a>
            </form>
        </div>
        <div class="loghi">
            <!-- <img src="../assets/img/h4-clients-img-01.png" alt=""> -->
            <div id="image1">
                <img src="../assets/img/h4-clients-img-03.png" alt="">
            </div>
                
            <div id="image2">
                <img src="../assets/img/h4-clients-img-05.png" alt="">
            </div>

            <div id="image3">
                <img src="../assets/img/h4-clients-img-07.png" alt="">
            </div>

            <div id="image4">
                <img src="../assets/img/h4-clients-img-01.png" alt="">
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../components/style/General";
    #box {
        width: 100%;
        height: 100vh;

        .contact{
            width: 39%;
            height: 60%;
            padding: 20px;
            display: block;
            float: left;
            background-size: cover;

            input {
                background-color: transparent;
            }

            #name,
            #email {
                margin-right: 24px;
                border: 0;
                width: 45%;
                border-bottom: 1px solid black;
            }
            #textarea {
                border: 0;
                width: 100%;
                height: 150px;
                border-bottom: 1px solid black;
            }
            #button {
                font-size: 15px;
                color: white;
                padding: 10px 25px;
                margin: 10px;
                text-transform: uppercase;
                font-family: 'Lato', sans-serif;
                border: 0;
                background-color: $orange;
                text-decoration: none;

            }
        }
        .loghi {
            width: 100%;
            height: 30%;
            display: block;
            float: left;
            display: flex;

            div {
                margin: 10px;
                width: calc((100% - 100px) / 4);
                //background-color: red;
                display: flex;
            }
            #image1:hover {
                background-size: cover;
                background-image: url(../assets/img/h4-clients-img-04-1.png);
                img {
                    display: none;
                }
            }
            #image2:hover {
                background-size: cover;
                background-image: url(../assets/img/h4-clients-img-06-1.png);
                img {
                    display: none;
                }
            }
            #image3:hover {
                background-size: cover;
                background-image: url(../assets/img/h4-clients-img-08-1.png);
                img {
                    display: none;
                }
            }
            #image4:hover {
                background-size: cover;
                background-image: url(../assets/img/h4-clients-img-02.png);
                img {
                    display: none;
                }
            }

        }
        .map {
            width: 61%;
            height: 57%;
            //margin-bottom: 10%;
            display: block;
            float: left;
            background-size: cover;
            background-image: url(../assets/img/h1-contact-rev-01.png);
            position: relative;
            background-size: cover;

            #immage1 {
                position: absolute;
                left: 23%;
                top: 35%;
                h1 {
                    font-size: 20px;
                    font-weight: 800;
                    margin: 5px;
                    padding: 15px;
                    font-family: 'Libre Baskerville', serif;
                    background-color: white;

                    p {
                        font-size: 15px;
                        font-weight: 800;
                        text-transform: uppercase;
                        font-family: 'Lato', sans-serif;
                        color: black;
                    }
                }
            }
            #immage2 {
                position: absolute;
                left: 50%;
                top: 25%;

            }
            #immage3 {
                position: absolute;
                left: 83%;
                top: 73%;

            }

        }
    }
    
</style>>

