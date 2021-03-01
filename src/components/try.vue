<template>
  <div class='wrapper'>
    <div class='content__wrapper'>
      <div class='content__header'>
        <h2>Try Nano and claim your first Nano today, for free!</h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'try'
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
      padding: 10% 0 0 10%;
      z-index: 1000;

      .content__header {
        font-size: 3vmin;
        font-weight: 700;
        color: white;
        text-align: left;
      }
    }
  }

</style>
