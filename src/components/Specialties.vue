<template>
  <section>
      <div>
          <h1>Our specialities<span>.</span></h1>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
          <span>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
              <i class="fas fa-minus"></i>
          </span>
      </div>
      <div id="section_image">
          <span class="image">
              <img src="../assets/svg/svg-0.svg" alt="">
              <h3>Knpwing</h3>
              <p>Lorem ipsum dolor sit amet, quis consect.</p>
          </span>

          <span class="image">
              <img src="../assets/svg/svg-1.svg" alt="">
              <h3>Selling</h3>
              <p>Lorem ipsum dolor sit amet, quis consect.</p>
          </span>

          <span class="image">
              <img src="../assets/svg/svg-2.svg" alt="">
              <h3>Learning</h3>
              <p>Lorem ipsum dolor sit amet, quis consect.</p>
          </span>

          <span class="image">
              <img src="../assets/svg/svg-3.svg" alt="">
              <h3>Contact</h3>
              <p>Lorem ipsum dolor sit amet, quis consect.</p>
          </span>
      </div>
  </section>
</template>

<script>
export default {
    name: "Specialties"

}
</script>

<style lang="scss" scoped>
@import "../components/style/General";
    section {
        width: 100%;
        padding: 60px 45px;
        background-color: white;

        div {
            text-align: center;
            span {
                color: $orange;
                i {
                    height: 20px;
                    margin: -1px;
                }
            }
            p {
                color: $greyText;
            }
        }
        #section_image {
            display: inline-block;

            .image {
                display: inline-block;
                text-align: center;

                h3 {
                    color: black;
                    font-weight: 700;
                    margin: 15px 0;
                    font-family: 'Libre Baskerville', serif;
                }
                p {
                    width: 80%;
                    display: block;
                    margin: 0 auto;
                }
            }
        }
    }
</style>>