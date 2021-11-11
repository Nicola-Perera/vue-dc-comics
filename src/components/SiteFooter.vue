<template>
    <div id="Footer">

      <!-- useful links -->
      <div id="link_section">
        <div class="container main_margin">
          <div class="row">

            <!-- links lists -->
            <div class="row links">
              <div>
                <h2>DC COMICS</h2>
                <ul>
                  <li><a href="">Characters</a></li>
                  <li><a href="">Comics</a></li>
                  <li><a href="">Movies</a></li>
                  <li><a href="">TV</a></li>
                  <li><a href="">Games</a></li>
                  <li><a href="">Videos</a></li>
                  <li><a href="">News</a></li>
                </ul>
              </div>

              <div>
                <h2>DC</h2>
                <ul>
                  <li><a href="">Terms Of Use</a></li>
                  <li><a href="">Privacy policy (New)</a></li>
                  <li><a href="">Ad Choices</a></li>
                  <li><a href="">Advertising</a></li>
                  <li><a href="">Jobs</a></li>
                  <li><a href="">Subscriptions</a></li>
                  <li><a href="">Talent Workshops</a></li>
                  <li><a href="">CPSC Certificate</a></li>
                  <li><a href="">Ratings</a></li>
                  <li><a href="">shop Help</a></li>
                  <li><a href="">Contact Us</a></li>
                </ul>
              </div>

              <div>
                <h2>SITE</h2>
                <ul>
                  <li><a href="">DC</a></li>
                  <li><a href="">MAD Magazine</a></li>
                  <li><a href="">DC Kids</a></li>
                  <li><a href="">DC Universe</a></li>
                  <li><a href="">DC Power Visa</a></li>
                </ul>
              </div>

              <div>
                <h2>SHOP</h2>
                <ul>
                  <li><a href="">Shop DC</a></li>
                  <li><a href="">Shop DC Collectibles</a></li>
                </ul>
              </div>
            </div>

            <!-- logo -->
            <div id="logo">
              <img src="../img/dc-logo-bg.png" alt="">
            </div>
        </div>
      </div>
    </div>

      <!-- socials -->
      <div id="social_section">

        <div class="container main_margin">
          <div class="row">
            <a id="sign" href="">SIGN-UP NOW!</a>
            <div id="socials" class="container">
              <div class="row">
              <a href="" id="follow">FOLLOW US</a>
              <a href=""><img src="../img/footer-facebook.png" alt=""></a>
              <a href=""><img src="../img/footer-twitter.png" alt=""></a>
              <a href=""><img src="../img/footer-youtube.png" alt=""></a>
              <a href=""><img src="../img/footer-pinterest.png" alt=""></a>
              <a href=""><img src="../img/footer-periscope.png" alt=""></a>
              </div>
            </div>
          </div>
        </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'footer',
  components: {

  },
};
</script>

<style lang="scss">

// links section
#link_section {
  background-image: url('../img/footer-bg.jpg');

  // links
  .row.links {
    width: 40%;
    flex-wrap: wrap;
    justify-content: space-between;
    font-size: .8rem;
  }
  .links {
      padding: 2rem 0;
    }

  h2 {
    color: white;
    margin-bottom: 1rem;
    }
  li {
    list-style: none;
    margin-bottom: .3rem;
    a {
      color: #797979;
    }
  }
      // logo in background
    #logo {
      width: 60%;
      height: 100%;
      background-image: url('../img/dc-logo-bg.png');
      background-size: cover;
      background-repeat: no-repeat;
      img {
        width: 70%;
      }
    }
  }

  // social section
  #social_section {
    padding: 1rem 0;
      background-color: #303030;
    .container.main_margin > .row {
      justify-content: space-between;
      align-items: center;
      #sign {
        padding: 1rem;
        color: white;
        border: 2px solid #0282F9;
      }
    #socials {
      width: 35%;
      .row {
          justify-content: space-between;
          align-items: center;
          #follow {
            color: #0282F9;
          }
        }
      }
    }
  }
</style>
