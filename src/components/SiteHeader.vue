<template>
    <div id="Header">
      <div class="container main_margin">
        <div class="row">

          <!-- dc logo -->
          <div id="logo">
            <img src="../img/dc-logo.png" alt="dc_logo_blue">
          </div>

          <!-- nav menu -->
          <div id="nav_menu" class="container">
            <div class="row">
              <div>
                <a href="">CHARACTERS</a>
              </div>

              <div class="active">
                <a href="">COMICS</a>
              </div>

              <div>
                <a href="">MOVIES</a>
              </div>

              <div>
                <a href="">TV</a>
              </div>

              <div>
                <a href="">GAMES</a>
              </div>

              <div>
                <a href="">COLLECTIBLES</a>
              </div>

              <div>
                <a href="">VIDEOS</a>
              </div>

              <div>
                <a href="">FANS</a>
              </div>

              <div>
                <a href="">NEWS</a>
              </div>

              <div>
                <a href="">SHOP</a>
              </div>
            </div>

          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: 'header',
  components: {

  },
};
</script>

<style lang="scss">
  #logo {
    width: 40%;
    padding: 1rem 0;
    }

#nav_menu {
  width: 60%;

  .row {
    width: 100%;
    justify-content: space-between;
    height: 100%;

    div {
      height: 100%;
      padding-top: 3rem;
    }
  }

  a {
    font-size: .8rem;
  }
}
</style>
