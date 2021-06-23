<template>
  <section>
      <div class="title">
          <h1>Latest news<span class="orange-class">.</span></h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
            <div class="line-space"></div>
      </div>
      <div class="image">
          <div class="section">
              <div class="box-image">
                  <img class="image1" src="../assets/img/h1-blog-img-02.jpg" alt="image1">
                  <img class="image2" src="../assets/img/h1-blog-img-03.jpg" alt="image2">
              </div> 
              <p>
                  <span class="orange-class">
                    <i class="far fa-clock"></i>
                  </span> 
                    May 5, 2019
                  <span class="orange-class">
                    <i class="far fa-user"></i>
                  </span> 
                    Amanda Doe
              </p>
              <h1>Next investment</h1>
              <p>Lorem, ipsum dolor sit amet adipisicing elit. Voluptates blanditiis...</p>
              <h3>read more</h3>
          </div>
          <div class="section">
              <div class="box-image">
                  <img class="image1" src="../assets/img/h1-blog-img-03.jpg" alt="image1">
                  <img class="image2" src="../assets/img/h1-blog-img-04.jpg" alt="image2">
              </div> 
              <p>
                  <span class="orange-class">
                    <i class="far fa-clock"></i>
                  </span> 
                    May 5, 2019
                  <span class="orange-class">
                    <i class="far fa-user"></i>
                  </span> 
                    Amanda Doe
              </p>
              <h1>Team Bulding</h1>
              <p>Lorem, ipsum dolor sit amet adipisicing elit. Voluptates blanditiis...</p>
              <h3>read more</h3>
          </div>
          <div class="section">
              <div class="box-image">
                  <img class="image1" src="../assets/img/h1-blog-img-03.jpg" alt="image1">
                  <img class="image2" src="../assets/img/h1-blog-img-01.jpg" alt="image2">
              </div> 
              <p>
                  <span class="orange-class">
                    <i class="far fa-clock"></i>
                  </span> 
                    May 5, 2019
                  <span class="orange-class">
                    <i class="far fa-user"></i>
                  </span> 
                    Amanda Doe
              </p>
              <h1>New Business Day</h1>
              <p>Lorem, ipsum dolor sit amet adipisicing elit. Voluptates blanditiis...</p>
              <h3>read more</h3>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name:"News",
}
</script>

<style lang="scss" scoped>
@import "../components/style/General";
    section {
        width: 100%;
        padding: 50px;

        .title {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;

            p {
                margin: 15px 0;
            }
        }
        .image {
            .section {
                display: inline-block;
                width: calc((100% - 60px) / 3 );
                img {
                    width: 100%;
                }
                .box-image {
                    position: relative;
                    margin: 10px;
                    //width: calc((100% - 60px) / 3 );
                    .image1 {
                        position: absolute;
                        clip: rect(0px, 396px, 104px, 0px);
                    }
    
                }

                h3 {
                    font-size: 20px;
                    font-weight: 700;
                    text-transform: uppercase;
                }
    
            }
        }
    }
</style>>