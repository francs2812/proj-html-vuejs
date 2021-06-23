<template>
  <section>
        <div class="calendar">
            <h1>Upcoming Events</h1>
            <Day 
            numberDay="07" 
            attivityDay="Melbourne Coaching" 
            clock=" 9:am - 5 pm, Jan 7, 2022"
            position="Cambridge, MA 02138, USA"
            />

            <Day 
            numberDay="11" 
            attivityDay="New York Coaching" 
            clock=" 9:am - 5 pm, Jan 11, 2022"
            position="Cambridge, MA 02138, USA"
            />

            <Day 
            numberDay="21" 
            attivityDay="London Coaching" 
            clock=" 9:am - 5 pm, Jan 7, 2022"
            position="Cambridge, MA 02138, USA"
            />

        </div>
  </section>
</template>

<script>
import Day from './Day.vue'
export default {
  components: { Day },

}
</script>

<style lang="scss" scoped>
@import "../components/style/General";

    section {
        width: 100%;
        height: 100vh;
        padding-top: 7%;
        padding-left: 17%;
        background-size: cover;
        background-image: url(../assets/img/h1-img-09.jpg);

        .calendar {
            width: 40%;
            background-color: white;

            h1 {
                width: 100%;
                height: 50px;
                padding: 15px;
                font-size: 17px;
                font-weight: 700;
                text-align: left;
                background-color: $grey;
                font-family: 'Libre Baskerville', serif;
            }
        }
    }
</style>>