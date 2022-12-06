<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg bg-light p-0">
      <div
        class="container-fluid navbar-toggleable-md flex-sm-row-reverse flex-row-reverse flex-lg-row-reverse flex-xl-row p-0"
      >
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <router-link class="navbar d-block d-sm-block d-lg-none" to="/contact">
            <button
              class="btn btn-basic btn-outline-light"
            >
              <img src="./assets/top-m-icon.png" alt class="img-fluid" />
            </button>
          </router-link>

        <router-link class="navbar-brand" to="/">
          <a class="btn btn-basic btn-outline-light">
            <img src="./assets/elogo.svg" width="195" alt class="img-fluid align-center" />
          </a>
        </router-link>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mx-auto mb-2 mb-lg-0 text-center navbar-nav-scroll">
            <li class="nav-item">
              <router-link class="nav-link active" aria-current="page" to="/">Home</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" aria-current="page" to="/about">About</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" aria-current="page" to="/service">Services</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" aria-current="page" to="/contact">Contact</router-link>
            </li>
          </ul>
          <router-link class="navbar d-none d-sm-none d-lg-block" to="/contact">
            <button
              class="btn btn-basic btn-outline-light"
            >
              <img src="./assets/top-m-icon.png" alt class="img-fluid" />
            </button>
          </router-link>
        </div>
      </div>
    </nav>
    <router-view />
    <Footer />
  </div>
</template>
<script>
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    Footer
  }
};
</script>

