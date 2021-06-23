<template>
  <main>
      <div id="specialties">
          <Specialties />
      </div>

      <div>
          <Founder />
      </div>

      <div>
          <Calendar />
      </div>

      <div>
          <Leader />
      </div>

      <div>
          <News />
      </div>

      <div>
          <Review />
      </div>

      <div>
          <Video />
      </div>

      <div>
          <Contacs />
      </div>
    

  </main>
</template>

<script>
import Specialties from '../components/Specialties.vue'
import Founder from './Founder.vue'
import Calendar from './Calendar.vue'
import Leader from './Leader.vue'
import News from './News.vue'
import Review from './Review.vue'
import Video from './Video.vue'
import Contacs from './Contacs.vue'


export default {
    name: "Main",
    components: {
        Specialties,
        Founder,
        Calendar,
        Leader,
        News,
        Review,
        Video,
        Contacs
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