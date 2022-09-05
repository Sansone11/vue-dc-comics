<template>
  <footer>
    <div class="contact">
      <div>

      </div>
      <div class="contact-wrapper">
        <h3>DC COMICS</h3>
        <div>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">Tv</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <h3>SHOP</h3>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>
        <h3>DC</h3>
        <div>
          <ul>
            <li><a href="#">Term Of Use </a></li>
            <li><a href="#">Privacy policy (New)</a></li>
            <li><a href="#">Ad Choise</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscription</a></li>
            <li><a href="#">Talent Workshop</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shpo Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
        <h3>SITES</h3>
        <div>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="follow-us">
      <div class="button">
        <button id="push">SIGN-UP-NOW</button>
      </div>
      <div class="social-contact">
        <h2>FOLLOW-US</h2>
        <ul>
          <li class="icon"><img src="../assets/img/footer-facebook.png" alt=""></li>
          <li class="icon"><img src="../assets/img/footer-twitter.png" alt=""></li>
          <li class="icon"><img src="../assets/img/footer-youtube.png" alt=""></li>
          <li class="icon"><img src="../assets/img/footer-periscope.png" alt=""></li>
          <li class="icon"><img src="../assets/img/footer-pinterest.png" alt=""></li>
        </ul>
      </div>

    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style lang="scss" scoped>
@import './Style/varaibles.scss';

footer {
  display: flex;
  flex-direction: column;
  min-height: 200px;
  width: 100%;
}

.contact {
  min-height: 350px;
  background-image: url(@/assets/img/footer-bg.jpg);
  background-size: cover;
  background-position: center;
  display: flex;
  flex-direction: row;
  color: gray;
  flex-basis: 50%;

  h3 {
    color: white;
  }

}

.contact-wrapper {
  display: flex;
  // flex-direction: row;
  justify-items:flex-end;
  align-content: center;

  li &a {
    font-size: 12px;
  }
}

.follow-us {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: $bg-footer-nav;
  min-height: 100px;
  flex-basis: 50%;

  ul {
    display: flex;
    gap: 2rem;
    width: 200px;
  }

  li {
    height: 70px;
    width: 70px;
    border-radius: 50%;
  }
}
</style>
