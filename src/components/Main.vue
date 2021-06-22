<template>
  <main>
      <div id="specialties">
          <Specialties />
      </div>
      <div>
          <h1>
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Non velit exercitationem consequatur reiciendis eaque, aspernatur iure omnis, asperiores repellendus labore dignissimos eos error est tempora saepe voluptates eius, similique corrupti id laboriosam. Nesciunt tenetur ea cum soluta sapiente cupiditate dolores, saepe ad perferendis laboriosam ipsum voluptatum enim, excepturi debitis iure.

          </h1>
      </div>
  </main>
</template>

<script>
import Specialties from '../components/Specialties.vue'
export default {
    name: "Main",
    components: {
        Specialties
  }

}
</script>

<style lang="scss" scoped>
@import "../components/style/General";
 main {
     width: 100%;
     background-color: $grey;

     #specialties {
        width: 95%;
        transform: translate(0%, -25%);
        text-align: center;
        margin: 0 auto;

     }


 }
</style>