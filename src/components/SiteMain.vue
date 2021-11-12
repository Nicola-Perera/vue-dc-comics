<template>
  <div id="SiteMain">
    <!-- content -->
    <div id="main_content">
      <!-- hero image -->
      <div class="jumbotron">
            <div class="series">
              <h2>CURRENT SERIES</h2>
            </div>
      </div>
      <div class="main_margin">
            <Card />
            <button id="load">LOAD MORE</button>
      </div>
    </div>

    <!-- shop and subscription -->
    <div id="purchase">
      <div class="container main_margin">
        <div class="row">
          <div>
            <img src="../img/buy-comics-digital-comics.png" alt="" />
            <a href="">DIGITAL COMICS</a>
          </div>
          <div>
            <img src="../img/buy-comics-merchandise.png" alt="" />
            <a href="">DC MERCHANDISE</a>
          </div>
          <div>
            <img src="../img/buy-comics-subscriptions.png" alt="" />
            <a href="">SUBSCRIPTION</a>
          </div>
          <div>
            <img src="../img/buy-comics-shop-locator.png" alt="" />
            <a href="">COMIC SHOP LOCATOR</a>
          </div>
          <div class="row">
            <img src="../img/buy-dc-power-visa.svg" alt="" />
            <a href="">DC POWER VISA</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Card from './Card.vue';

export default {
  name: 'SiteMain',
  components: {
    Card,
  },
};
</script>

<style lang="scss">
#main_content {
  background-color: #1c1c1c;
  padding-bottom: 3rem;
  .jumbotron {
    background-image: url("../img/jumbotron.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    padding: 9rem 0;
    position: relative;
    .series {
      background-color: #0282f9;
      padding: .8rem;
      position: absolute;
      left: 7rem;
      top: 16.5rem;
      h2 {
        color: white;
      }
    }
  }
  .main_margin {
    padding-top: 3rem;
    text-align: center;
    #load {
      background-color: #0282f9;
      color: white;
      padding: .5rem 3rem;
      margin-top: 2rem;
    }
  }
}
#purchase {
  background-color: #0282f9;
  a {
    font-size: 0.8rem;
    color: white;
  }
  img {
    height: 40%;
  }
  .row {
    padding: 0 2rem;
    div {
      display: flex;
      align-items: center;
      &:last-child img {
        height: 30%;
      }
    }
  }
}
</style>
