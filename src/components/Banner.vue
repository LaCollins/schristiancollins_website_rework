<template>
  <div class="banner">
    <img alt="S. Christian Collins, Pianist, Composer, Virtual Instrument Designer"
    :src="require('../assets/images/banner.jpg')" />
    <div id="nav">
      <b-navbar toggleable="md" type="dark">
        <b-navbar-brand></b-navbar-brand>
        <b-navbar-toggle target="nav-collapse" class="mr-auto"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item><router-link to="/">Home</router-link></b-nav-item>
            <b-nav-item><router-link to="/about">About</router-link></b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Banner',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

#nav {
  width: 600px;
  padding-top: 0px;
  font-size: 1.5em;
}

.bg-foobar {
  background-color: black;
}

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
  text-decoration: none;
}
</style>
