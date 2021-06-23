<template>
  <div class="card">
      <div class="day">
          <h1> {{ numberDay }} </h1>
          <p>Jan.2022</p>
      </div>
      <div class="text">
        <h2> {{ attivityDay }} </h2>
        <p>
            <span>
                <i class="far fa-clock"></i>
            </span> 
            {{ clock }}
        </p>

        <p>
            <span>
                <i class="fas fa-map-marker-alt"></i>
            </span> 
            {{ position }}
        </p>
        <h3>read more</h3>

      </div>

  </div>
</template>

<script>
export default {
    name: "Day",
    props: {
        numberDay: String,
        attivityDay: String,
        clock: String,
        position: String
    }

}
</script>

<style lang="scss" scoped>
@import "../components/style/General";

    .card {
        width: 100%;
        height: 32%;
        padding: 15px;
        display: flex;
        text-align: left;
        flex-direction: row !important;
        align-items: flex-start;
        flex-wrap: wrap;
    }
    .day {
        width: 30%;
        padding: 5px;
        float: left;
        text-align: center;
        color: white;
        background-color: $orange;

        h1 {
            font-size: 20px;
        }
        p {
            font-size: 15px;
            margin: 0;
        }
    }
    .text {
        width: 60%;
        margin: 0 15px;
        h2{
            font-size: 20px;
        }
        p {
            font-size: 14px;
            margin: 10px 0;
            span {
                color: $orange;
            }
        }

        h3 {
            font-size: 20px;
            font-weight: 700;
            text-transform: uppercase;
        }
    }


</style>