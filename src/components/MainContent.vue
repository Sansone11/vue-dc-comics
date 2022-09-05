<template>
  <main>
    <div class="container">

    </div>
    <div class="icons-bar">
      <div class="icon-logo">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <h4>DIGITAL COMICS</h4>
      </div>

      <div class="icon-logo">
        <img src="../assets/img/buy-comics-merchandise.png" alt="">
        <h4>DC MERCHANDISING</h4>
      </div>
      <div class="icon-logo">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        <h4>SUBSCRIPTION</h4>
      </div>
      <div class="icon-logo">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
        <h4>COMICS SHOP LOCATION</h4>
      </div>
      <div class="icon-logo">
        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
        <h4>DC POWER VISA</h4>
      </div>
    </div>
  </main>
</template>

<script>
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import './Style/varaibles.scss';

.container {
  height: 170px;
  background-color: $bg-main-content-bl;
  
}

.icons-bar {
  height: 170px;
  background-color: $bg-active;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  gap: 4rem;
}

.icon-logo{
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 2rem;
  img {
    height: 50px;
    width: 50px;
  }
  h4 {
    font-size: 12px;
  }
}
</style>