<template lang="html">
  <div id="main-header" uk-sticky>
    <nav id="content-desktop" class="uk-navbar-container" uk-navbar>

      <div class="uk-navbar-left uk-margin-left">

        <ul class="uk-navbar-nav">
          <li class="uk-active">
            <router-link to="/"><img src="http://www.jamalco.com/jamalco/img/logo.png" alt="Jamalco logo"></router-link>
          </li>
        </ul>

      </div>

      <div class="uk-navbar-right uk-margin-right">
        <ul class="uk-navbar-nav">
          <li class=""><router-link :to="{ name: 'Home'}">Home</router-link></li>
          <li class=""><router-link :to="{ name: 'About'}">About Us</router-link></li>
          <li class=""><router-link :to="{ name: 'Contact'}">Contact Us</router-link></li>
          <li class=""><router-link :to="{ name: 'Community'}">Community</router-link></li>
          <li class=""><router-link :to="{ name: 'Responsibility'}">Responsibility</router-link></li>
          <li class=""><router-link :to="{ name: 'AluminaIndustry'}">Alumina Industry</router-link></li>
          <li class=""><router-link :to="{ name: 'Careers'}">Careers</router-link></li>
          <li class=""><router-link :to="{ name: 'News'}">News</router-link></li>
        </ul>
      </div>

    </nav>

    <nav id="content-mobile" class="uk-navbar uk-navbar-container">

      <div class="uk-navbar-left">
        <ul class="uk-navbar-nav">
          <li class="uk-active">
            <router-link to="/"><img src="http://www.jamalco.com/jamalco/img/logo.png" alt="Jamalco logo"></router-link>
          </li>
        </ul>
      </div>

      <div class="uk-navbar-right">
        <a class="uk-navbar-toggle" uk-toggle="target: #offcanvas-menu" uk-navbar-toggle-icon href="#"></a>
      </div>

      <div id="offcanvas-menu" uk-offcanvas>
        <div class="uk-offcanvas-bar">

          <button class="uk-offcanvas-close" id="uk-close" type="button" uk-close></button>

          <h3>Menu</h3>

          <ul class="uk-list">
            <li class="" @click="close"><router-link :to="{ name: 'Home'}">Home</router-link></li>
            <li class="" @click="close"><router-link :to="{ name: 'About'}">About Us</router-link></li>
            <li class="" @click="close"><router-link :to="{ name: 'Contact'}">Contact Us</router-link></li>
            <li class="" @click="close"><router-link :to="{ name: 'Community'}">Community</router-link></li>
            <li class="" @click="close"><router-link :to="{ name: 'Responsibility'}">Responsibility</router-link></li>
            <li class="" @click="close"><router-link :to="{ name: 'AluminaIndustry'}">Alumina Industry</router-link></li>
            <li class="" @click="close"><router-link :to="{ name: 'Careers'}">Careers</router-link></li>
            <li class="" @click="close"><router-link :to="{ name: 'News'}">News</router-link></li>
          </ul>

        </div>
      </div>

    </nav>
  </div>
</template>

<script>
export default {
  methods: {
    close() {
      document.getElementById("uk-close").click()
    }
  }
}
</script>

<style lang="css" scoped>
#nav a {
  color: #000000;
}

li a.router-link-exact-active {
  color: #008000;
  font-weight: bold;
}

a {
  position: relative;
  color: #000;
  text-decoration: none;
}

a:hover {
  color: #000;
}

a::before {
  content: "";
  position: absolute;
  width: 100%;
  height: 2px;
  bottom: 0;
  left: 0;
  background-color: #000;
  visibility: hidden;
  transform: scaleX(0);
  transition: all 0.3s ease-in-out 0s;
}

a:hover::before {
  visibility: visible;
  transform: scaleX(1);
}

#content-desktop {
  background-color: #FFFFFF;
}
#content-mobile {
  background-color: #FFFFFF;
}

@media screen and (min-width: 1053px) {

  #content-desktop {visibility: visible;}
  #content-mobile {display: none;}

}


@media screen and (max-width: 1052px) {

  #content-desktop {display: none;}
  #content-mobile {visibility: visible;}

}
</style>
