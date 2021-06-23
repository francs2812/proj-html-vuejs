<template>
  <section>
      <img id="img1" src="../assets/img/h1-blog-img-04.jpg" alt="foto">
      <div class="textbox">
          <h1>Jason Bickford</h1>
          <p>Founder and Executive Director</p>
        
          <span>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
          </span>

          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore architecto quia  ....</p>
          <span>
              <i class="fab fa-linkedin-in "></i>
              <i class="fab fa-facebook-f "></i>
              <i class="fab fa-twitter "></i>
          </span>
      </div>
          <img id="img2" src="../assets/svg/svg-4.svg" alt="">
  </section>
</template>

<script>
export default {
    name: "Founder"

}
</script>

<style lang="scss" scoped>
@import "../components/style/General";

    section {
        display: inline-block;
        width: 100%;
        height: 500px;
        position: relative;
        padding: 20px;

        #img1 {
            height: 400px;
            position: absolute;
            transform: translate(-50%, -50%);
            left: 30%;
            top: 50%;
        }
        .textbox {
            width: 500px;
            height: 325px;
            padding: 30px;
            background-color: white;
            transform: translate(-50%, -50%);
            position: absolute;
            left: 65%;
            top: 50%;
            z-index: 3;

            h1 {
                font-family: 'Libre Baskerville', serif;
            }
            p {
                color: $greyText;
            }
            span {
                color: $orange;
                .fas{
                    height: 20px;
                    margin: -1px;
                }
            }
            span {
                .fa-twitter {
                    margin: 10px;
                    padding: 8px;
                    font-size: 13px;
                    border-radius: 50%;
                    color: white;
                    background-color: $orange;
                }
                .fab {
                    margin: 10px;
                    padding: 8px 10px;
                    font-size: 13px;
                    border-radius: 50%;
                    color: white;
                    background-color: $orange;
                }
            }

        }
            #img2 {
                position: absolute;
                transform: translate(-50%, -50%);
                left: 80%;
                top: 25%;
                z-index: 0;
            }
    }
</style>>