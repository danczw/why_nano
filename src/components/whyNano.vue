<template>
  <div class='wrapper'>
    <div class='content-wrapper'>
      <div class='content-header'>
        <h2>Experience the future of money today.</h2>
      </div>
      <div class='content-text'>
        Try NANO now
      </div>
    </div>
    <div class='learn-more'>
      learn more
    </div>
  </div>
</template>

<script>
export default {
  name: 'whyNano'
}
</script>

<style lang='scss' scoped>
  .wrapper {
    height: 100vh;
    background:linear-gradient(0deg, rgba(0, 0, 0, 0.9), rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.9)), url('../assets/lake.gif');
    background-repeat: repeat;
    background-position: center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;

    .content-wrapper {
      padding: 20%;
      z-index: 1000;

      .content-text {
        color: #4A90E2;
        font-size: 40px;
        font-weight: 700;
        text-align: center;
      }

      h2 {
        font-size: 40px;
        font-weight: 700;
        color: white;
      }
    }
    .learn-more {
      color: rgb(109, 109, 109);
    }
  }

</style>
