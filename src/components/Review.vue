<template>
    <section>
        <h1>Testimonials</h1>
        <img src="../assets/img/h3-img-04.png" alt="">
        <div id="box-rec">
            <h4>Cynthia Clark</h4>
            <p>"Lorem ipsum dolor sit amet consectetur, adipisicing elit. Veniam sint illo laborum ea illum adipisci nulla recusandae"</p>
            <div>
                <span>01</span>
                <div>
                    <div></div>
                </div>
                <span>03</span>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Review"
}
</script>

<style lang="scss" scoped>
@import "../components/style/General";

        section {
            width: 100%;
            height: 500px;
            padding: 50px;
            background-color: #191516;
            position: relative;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;

            h1 {
                font-size: 150px;
                font-family: 'Libre Baskerville'
            }
            img {
                transform: translate(-50%, -50%);
                position: absolute;
                left: 52%;
                top: 45%;
            }

        }
        #box-rec {
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            p {
                width: 50%;
            }

            h4 { 
                color: white;
            }
            div {
                width: 300px;
                display: flex;
                justify-content: space-between;
                align-items: center;

                span {
                    font-family: 'Libre Baskerville', serif;
                    color: $greyText;
                    width: 10%;
                    margin: 10px;
                }

                div {
                    display: block;
                    width: 70%;
                    height: 5px;
                    border-radius: 3px;
                    background-color: $grey;
                    div {
                        display: block;
                        width: 30%;
                        background-color: $greyText;

                    }
                }
            }
        }
</style>>
