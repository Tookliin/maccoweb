<template>
  <div id="app">
    <main class>
     <mdb-navbar position="top" dark transparent scrolling>
     
      <mdb-navbar-toggler>
        <mdb-navbar-nav>

        <a class="navbar-brand" href="/">DevME</a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarColor01"
          aria-controls="navbarColor01"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarColor01">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item">
              <router-link class="nav-link" to="/contact"
                >Contact Me</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/projects"
                >Projects</router-link
              >
            </li>

          </ul>
        </div>
            <!-- <ul class="navbar-nav nav-flex-icons ml-auto">
      <li class="nav-item">
        <a class="nav-link" href="#!">
          <i class="fab fa-facebook-f" aria-hidden="true"></i>
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#!">
          <i class="fab fa-twitter" aria-hidden="true"></i>
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#!">
          <i class="fab fa-instagram" aria-hidden="true"></i>
        </a>
      </li>
    </ul> -->
        </mdb-navbar-nav>
     
      </mdb-navbar-toggler>
    </mdb-navbar>
    </main>

    <router-view></router-view>
  </div>
</template>
<style lang="css" scoped>
</style>

<script>
 import {
    mdbNavbar,
    
    mdbNavbarNav,
    mdbNavbarToggler,
   
  } from "mdbvue";
export default {
  name: "App",
  components: {
     mdbNavbar,
   
      mdbNavbarNav,
      mdbNavbarToggler,
  },
  data() {
    return {};
  },
};
</script>