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
            <!-- <div id="logo">
              <img src="../img/dc-logo-bg.png" alt="">
            </div> -->
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
#link_section {
  background-image: url('../img/footer-bg.jpg');
  padding: 2rem 0;
  .row.links {
    width: 40%;
    flex-wrap: wrap;
    justify-content: space-between;
    font-size: .8rem;
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
  }
</style>
