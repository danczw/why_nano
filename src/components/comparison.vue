<template>
  <div class="wrapper__one">
    <div class='content__wrapper'>
      instant
    </div>
  </div>
  <div class="wrapper__two">
    <div class='content__wrapper'>
      fee-less
    </div>
  </div>
  <div class="wrapper__three">
    <div class='content__wrapper'>
      eco-friendly
    </div>
  </div>
</template>

<script>
export default {
  name: 'comparison'
}
</script>

<style lang='scss' scoped>
  .wrapper__one {
    height: 100vh;
    background:linear-gradient(0deg, rgba(0, 0, 0, 1), rgba(0, 0, 52, 0.7), rgba(0, 0, 52, 1) );
    background-repeat: repeat;
    background-position: center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    color: white;

    .content__wrapper {
      padding: 10%;
      z-index: 1000;
    }
  }

  .wrapper__two {
    height: 100vh;
    background:linear-gradient(0deg, rgba(0, 0, 52, 1), rgba(0, 0, 52, 0.7), rgba(0, 0, 0, 1) );
    background-repeat: repeat;
    background-position: center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    color: white;

    .content__wrapper {
      padding: 10%;
      z-index: 1000;
    }
  }

  .wrapper__three {
    height: 100vh;
    background:linear-gradient(0deg, rgba(0, 0, 0, 1), rgba(0, 0, 52, 0.7), rgba(0, 0, 52, 1));
    background-repeat: repeat;
    background-position: center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    color: white;

    .content__wrapper {
      padding: 10%;
      z-index: 1000;
    }
  }
</style>
