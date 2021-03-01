<template>
  <div class='wrapper__one'>
    <div class='content__wrapper'>
      <div class='content__text'>
        <p>Traditional, government-backed currencies and financial systems are constrained by <strong class="highlight">slow</strong>, <strong class="highlight">geographically limited</strong> and <strong class="highlight">third-party relient</strong> transactions.</p>
      </div>
    </div>
  </div>

  <div class="wrapper__two">
    <div class='content__wrapper'>
      <div class='content__text'>
        <p>Current established cryptocurrencies such as Bitcoin try to solve these constrains - <strong class="highlight"> only to run into new limitations:</strong></p>
      </div>

      <div class="content__disadv">
        <div class="content_disadv-item">
          <img src="../assets/placeholder.png" alt="">
          <h3>Limited transaction volume</h3>
          <p>
            Current technology used heavily limits the number of transactions that can be processed per second.
            <br>
            <br>
            High demand leads to longer waiting times for a transaction to be processed and verified.
          </p>
        </div>
        
        <div class="content_disadv-item">
          <img src="../assets/placeholder.png" alt="">
          <h3>Increasing transaction fees</h3>
          <p>
            With rising demand, fees increase for transactions to "jump the line" and be processed in the next available spot.
          </p>
        </div>
        
        <div class="content_disadv-item">
          <img src="../assets/placeholder.png" alt="">
          <h3>Heavy energy consumption</h3>
          <p>
            Transaction processing and verification often rely on mining or minting,which results in high power consumption for the hardware required for this purpose.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'problem'
}
</script>

<style lang='scss' scoped>
  .wrapper__one {
    height: 100vh;
    background:linear-gradient(0deg, rgba(0, 0, 52, 1), rgba(0, 0, 20, 0.6), rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 1)), url('../assets/situation.gif');
    background-repeat: repeat;
    background-position: center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;

    .content__wrapper {
      padding: 15% 10% 10% 10%;
      z-index: 1000;

      .content__text {
        color: white;
        font-size: 3vmin;
        padding-right: 30%;
        padding-top: 30%;
        font-weight: 700;
        text-align: left;

        .highlight {
          color: #4A90E2;
        }
      }
    }
  }

  .wrapper__two {
    height: 100vh;
    background:linear-gradient(0deg, rgba(12, 91, 180, 1), rgba(12, 91, 180, 0.4), rgba(0, 0, 52, 0.8), rgba(0, 0, 52, 1)), url('../assets/server.jpg');
    background-repeat: repeat;
    background-position: center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;

    .content__wrapper {
      padding: 15% 10% 10% 10%;
      z-index: 1000;

      .content__text {
        color: white;
        font-size: 3vmin;
        padding-right: 30%;
        padding-top: 5%;
        font-weight: 700;
        text-align: left;

        .highlight {
          color: #4A90E2;
        }
      }

      .content__disadv {
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        padding-top: 100px;

        .content_disadv-item {
          display: flex;
          flex-direction: column;
          color: white;
          text-anchor: middle;
          width: 20%;

          h3 {
            color: orange;
            font-size: 2vmin;
          }

          p {
            font-size: 1.6vmin;
            text-align: justify;
            color: rgb(214, 214, 214);
          }

          img {
            width: 15vmin;
            margin-left: auto;
            margin-right: auto;
            padding-top: 5px;
          }
        }
      }
    }
  }

</style>
