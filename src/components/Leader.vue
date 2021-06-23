<template>
  <section>
      <div class="text">
          <h1>Creative Leader<span>.</span></h1>

          <span>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
          </span>

          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Optio, sapiente eum. Asperiores magni voluptates expedita modi ab quidem atque dolore. Magni expedita, deleniti numquam excepturi cum eos rem officiis.
          </p>
          <h3>read more</h3>
      </div>
      <div class="graphic">

          <div>
              <h1>Mentorship <p>78%</p></h1>
              <div>
                  <div class="barra"><span style="width:78%"> </span></div>
              </div>
          </div>

          <div>
              <h1>Education <p>95%</p></h1>
              <div>
                  <div class="barra"><span style="width:95%"></span></div>
              </div>
          </div>

          <div>
              <h1>Learning <p>65%</p></h1>
              <div>
                  <div class="barra"><span style="width:65%"></span></div>
              </div>
          </div>

          <div>
              <h1>Motivation <p>83%</p></h1>
              <div>
                  <div class="barra"><span style="width:83%"></span></div>
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name: "Leader"
}
</script>

<style lang="scss" scoped>
@import "../components/style/General";
@import '../../node_modules/fontawesome-free/css/all.css';

        section {
            width: 100%;
            padding:5% 20%;
            background-color: white;

            .text {
                width: 50%;
                height: 100%;
                display: block;
                float: left;
                h1 {
                    font-weight: 700;
                    font-family: 'Libre Baskerville', serif;
                }

                span {
                    color: $orange;

                    i {
                        margin: -1px;
                    }
                }

                p {
                    color: $greyText;
                    font-family: 'Lato', sans-serif;
                }

                h3 {
                    font-size: 15px;
                    font-weight: 800;
                    text-transform: uppercase;

                }
            }
            .graphic {
                width: 50%;
                height: 100%;
                padding-left: 65px;
                display: block;
                float: left;
                //background-color: yellow;

                div {
                    h1 {
                        font-size: 20px;
                        font-weight: 700;
                        font-family: 'Libre Baskerville', serif;
                    }
                }

                .barra {
                    width: 100%;
                    height: 5px;
                    z-index: 2;
                    margin: 15px 0;
                    background-color: $grey;

                    span {
                        display: block;
                        height: 100%;
                        z-index: 3;
                        background-color: $orange;
                    }
                }
                p {
                    font-size: 20px;
                    float: right;
                }
            }
        }
</style>>