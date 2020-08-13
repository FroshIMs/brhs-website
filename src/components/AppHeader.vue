<template lang="html">
  <div id="nav">
    <nav class="uk-navbar-container uk-margin" uk-navbar>
      <div class="uk-navbar-center">
        <div class="uk-navbar-center-left"><div>
            <ul class="uk-navbar-nav">
                <li class="uk-active"><router-link to="/">Home</router-link></li>
                <li>
                    <a href="#">Admissions</a>
                    <div class="uk-navbar-dropdown">
                        <ul class="uk-nav uk-navbar-dropdown-nav">
                            <li class="uk-active"><a href="#">Active</a></li>
                            <li><a href="#">Item</a></li>
                            <li><a href="#">Item</a></li>
                        </ul>
                    </div>
                </li>

                <li>
                    <a href="#">Academic Programmes</a>
                    <div class="uk-navbar-dropdown">
                        <ul class="uk-nav uk-navbar-dropdown-nav">
                            <li class="uk-active"><a href="#">Active</a></li>
                            <li><a href="#">Item</a></li>
                            <li><a href="#">Item</a></li>
                        </ul>
                    </div>
                </li>
            </ul>
        </div></div>
        <a class="uk-navbar-item uk-logo" href="#">Logo</a>
          <div class="uk-navbar-center-right">
            <div>
              <ul class="uk-navbar-nav">
                <li>
                    <router-link to="/about">About</router-link>
                    <div class="uk-navbar-dropdown">
                        <ul class="uk-nav uk-navbar-dropdown-nav">
                            <li class="uk-active"><a href="#">Active</a></li>
                            <li><a href="#">Item</a></li>
                            <li><a href="#">Item</a></li>
                        </ul>
                    </div>
                </li>
                <li><a href="#">Contact Us</a></li>
                <li><a class="apply-link" href="#">Apply Now</a></li>
              </ul>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="less" scoped>
#nav {
  a {
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.apply {
  color: #42b989
}
</style>
