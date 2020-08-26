<template lang="html">
  <div id="nav">
    <nav id="main-nav" class="uk-navbar-container" uk-navbar>
      <div class="uk-navbar-center">
        <div class="uk-navbar-center-left"><div>
            <ul class="uk-navbar-nav">
                <li class="uk-active"><router-link to="/">Home</router-link></li>
                <li>
                    <a href="#">Admissions</a>
                    <div class="uk-navbar-dropdown">
                        <ul class="uk-nav uk-navbar-dropdown-nav">
                          <li class="uk-active"><router-link to="#">Application Forms</router-link></li>
                          <li><router-link to="#">Financial Aids</router-link></li>
                          <li><router-link to="#">Tuition & Fees</router-link></li>
                        </ul>
                    </div>
                </li>

                <li>
                    <a href="#">Academic Programmes</a>
                    <div class="uk-navbar-dropdown">
                        <ul class="uk-nav uk-navbar-dropdown-nav">
                          <li class="uk-active"><router-link to="#">Year Schedule</router-link></li>
                          <li><router-link to="#">Certificates</router-link></li>
                        </ul>
                    </div>
                </li>
            </ul>
        </div></div>
        <a class="uk-navbar-item uk-logo" href="#">BRHS</a>
          <div class="uk-navbar-center-right">
            <div>
              <ul class="uk-navbar-nav">
                <li>
                    <router-link to="/about">About</router-link>
                    <div class="uk-navbar-dropdown">
                        <ul class="uk-nav uk-navbar-dropdown-nav">
                          <li class="uk-active"><router-link to="#">Meet Our Leaders</router-link></li>
                          <li><router-link to="#">Who We Are</router-link></li>
                        </ul>
                    </div>
                </li>
                <li><a href="#">Contact Us</a></li>
                <li><a style="color: yellow; font-weight: bold;" href="#">Apply Now</a></li>
              </ul>
          </div>
        </div>
      </div>
    </nav>
    <AppTabs />
  </div>
</template>

<script>
import AppTabs from '@/components/AppTabs'

export default {
  components: {
    AppTabs
  }
}
</script>

<style lang="less" scoped>
#nav {
  a {
    color: #FFFFFF;

    &.router-link-exact-active {
      color: #FFFF00;
    }
  }
}
#main-nav {
  background-color: #000000
}
.uk-navbar-dropdown {
  background-color: #000000
}
</style>
