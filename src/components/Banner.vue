<template>
  <div class="banner">
    <img alt="S. Christian Collins, Pianist, Composer, Virtual Instrument Designer"
    :src="require('../assets/images/banner.jpg')" />
  </div>
</template>

<script>
export default {
  name: 'Banner',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 0px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
