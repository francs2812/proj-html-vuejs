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
    

  </main>
</template>

<script>
import Specialties from '../components/Specialties.vue'
import Founder from './Founder.vue'
import Calendar from './Calendar.vue'
import Leader from './Leader.vue'
import News from './News.vue'


export default {
    name: "Main",
    components: {
        Specialties,
        Founder,
        Calendar,
        Leader,
        News
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