<template>
  <v-app>
    <!-- <v-app-bar app color="primary" dark>123 </v-app-bar> -->

    <v-main>
      <router-view />
    </v-main>

    <div id="nav">
      <router-link to="/type1">type1</router-link> |
      <router-link to="/type2">type2</router-link> |
      <router-link to="/type3">type3</router-link> |
      <router-link to="/type4">type4</router-link> |
      <router-link to="/type5">type5</router-link> |
      <router-link to="/type6">type6</router-link> |
      <router-link to="/type7">type7</router-link> |
    </div>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>

<style lang="scss" scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
  margin: 0px auto;
}

</style>
