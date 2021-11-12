<template>
  <div id='CardLayout'>
    <img :src="image" alt="" />
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
</style>
