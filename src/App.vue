<template>
  <div id="app">
    <div class="mb-3">
      <b-navbar type="dark" variant="dark">
        <b-navbar-brand>Best Image</b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-item href="#" right
              ><i class="fab fa-github fa-2x"></i>
            </b-nav-item>
            <b-nav-item href="https://www.instagram.com/iiinaliniii/" target="blank" right>
              <i class="fab fa-instagram fa-2x"></i>
            </b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
    <Nasa />
  </div>
</template>

<script>
import Nasa from "./components/nasa";

export default {
  name: "App",
  components: {
    Nasa,
  },
};
</script>

<style>
#app {
  font-family: "Baloo Tammudu 2", cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
