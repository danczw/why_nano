<template>
  <div class='wrapper'>
    <div class='content__wrapper'>
      <div class='content__header'>
        <h2>Experience the future of money today.</h2>
      </div>
      <div class='content__text'>
        Try NANO now
      </div>
    </div>
    <div class="learn-more__wrapper">
      <div class='learn-more__item'>
        <img src="../assets/placeholder.png" alt="" class="learn-more__img">
        <div class="learn-more__text">experience the future, learn more about Nano</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'intro'
}
</script>

<style lang='scss' scoped>
  .wrapper {
    height: 100vh;
    background:linear-gradient(0deg, rgba(0, 0, 0, 1), rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 1)), url('../assets/lake.gif');
    background-repeat: repeat;
    background-position: center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;

    .content__wrapper {
      padding: 20%;
      z-index: 1000;

      .content__text {
        color: #4A90E2;
        font-size: 4vmin;
        font-weight: 700;
        text-align: center;
      }

      .content__header {
        font-size: 3vmin;
        font-weight: 700;
        color: white;
      }
    }

    .learn-more__wrapper {
      width: 100%;
      position: absolute;
      bottom: 0;

      .learn-more__item {
        color: rgb(230, 230, 230);
        width: 100%;

        .learn-more__text {
          text-anchor: middle;
        }

        .learn-more__img {
          height: 40px;
          margin-top: 10px;
        }
      }
    }
  }

</style>
