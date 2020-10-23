<template>
  <div id="app">
    <Banner />
    <router-view/>
  </div>
</template>

<script>
import Banner from '@/components/Banner.vue';

export default {
  components: {
    Banner,
  },
};
</script>

<style lang="scss">
body {
  background-image: url('./assets/images/bg-curtains.jpg');
  background-size: fill;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #fff;
    text-decoration: none;

    &.router-link-exact-active {
      color: rgb(131, 131, 131);
    }
  }
  a:hover {
    color: rgb(175, 108, 108);
  }
}
</style>
