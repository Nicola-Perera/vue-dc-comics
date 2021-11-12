<template>
  <div id='CardLayout'>
      <div class="serie_image">
        <img :src="image" alt="" />
      </div>
    <h3>{{ title }}</h3>
  </div>
</template>

<script>
export default {
  name: 'CardLayout',
  props: {
    image: String,
    title: String,
  },
};
</script>

<style lang='scss'>
#CardLayout {
    margin: 1rem 0;
    h3 {
        margin-top: .5rem;
        color: white;
        font-size: .8rem;
    }
    .serie_image {
        width: 100%;
        img {
            width: 500%;
        }
    }
}
</style>
