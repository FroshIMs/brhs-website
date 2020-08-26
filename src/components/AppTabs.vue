<template lang="html">
  <ul class="uk-container uk-flex-center uk-margin-remove" uk-tab>
    <li>
        <a href="#">Students<span class="" uk-icon="icon: triangle-down"></span></a>
        <div class="uk-width-large" uk-dropdown>
          <div class="uk-dropdown-grid uk-child-width-1-2@m" uk-grid>
              <div>
                  <ul class="uk-dropdown-nav uk-list uk-list-collapse">
                    <li class="uk-nav-header">Prospective Students</li>
                    <li class="uk-nav-divider"></li>
                    <li class="uk-active"><router-link to="#">School Map</router-link></li>
                    <li><router-link to="#">Financial Aid</router-link></li>
                    <li><router-link to="#">Student Handbook</router-link></li>
                    <li><router-link to="#">Clubs</router-link></li>
                    <li class="uk-nav-header">Current Students</li>
                    <li class="uk-nav-divider"></li>
                    <li class="uk-active"><router-link to="#">Fedorae SMS</router-link></li>
                    <li><router-link to="#">F-SMS Training</router-link></li>
                    <li><router-link to="#">Graduation Requirements</router-link></li>
                    <li><router-link to="#">Clubs</router-link></li>
                    <li class="uk-nav-header">School</li>
                    <li class="uk-nav-divider"></li>
                    <li class="uk-active"><router-link to="#">School Office Hours</router-link></li>
                    <li><router-link to="#">Public Safety</router-link></li>
                    <li><router-link to="#">Student Handbook</router-link></li>
                  </ul>
              </div>
          </div>
      </div>
    </li>
    <li>
        <a href="#">Parents & Alumni <span class="" uk-icon="icon: triangle-down"></span></a>
        <div class="uk-width-large" uk-dropdown>
          <div class="uk-dropdown-grid uk-child-width-1-2@m" uk-grid>
              <div>
                  <ul class="uk-nav uk-dropdown-nav">
                    <li class="uk-nav-header">Parents</li>
                    <li class="uk-nav-divider"></li>
                    <li class="uk-active"><router-link to="#">Academic Calendar</router-link></li>
                    <li><router-link to="#">Events Calendar</router-link></li>
                    <li><router-link to="#">News</router-link></li>
                    <li class="uk-nav-header">Alumni</li>
                    <li class="uk-nav-divider"></li>
                    <li><router-link to="#">Graduation</router-link></li>
                    <li><router-link to="#">Transcripts</router-link></li>
                  </ul>
              </div>
          </div>
      </div>
    </li>
    <li>
        <a href="#">Staff<span class="" uk-icon="icon: triangle-down"></span></a>
        <div uk-dropdown="mode: hover">
            <ul class="uk-nav uk-dropdown-nav">
              <li class="uk-active"><router-link to="#">Fedorae SMS</router-link></li>
              <li><router-link to="#">Careers</router-link></li>
              <li><router-link to="#">Internal Directory</router-link></li>
            </ul>
        </div>
    </li>
    <li>
        <a href="#">News and Events<span class="" uk-icon="icon: triangle-down"></span></a>
        <div uk-dropdown="mode: hover">
            <ul class="uk-nav uk-dropdown-nav">
              <li class="uk-active"><router-link to="#">Academic Calendar</router-link></li>
              <li><router-link to="#">Events Calendar</router-link></li>
              <li><router-link to="#">Feature Stories</router-link></li>
              <li><router-link to="#">News</router-link></li>
            </ul>
        </div>
    </li>
    <li>
        <a href="#">Departments & Services<span class="" uk-icon="icon: triangle-down"></span></a>
        <div uk-dropdown="mode: hover">
            <ul class="uk-nav uk-dropdown-nav">
              <li class="uk-nav-header">Departments</li>
              <li class="uk-nav-divider"></li>
              <li class="uk-active"><router-link to="#">Computer</router-link></li>
              <li class="uk-nav-header">Services</li>
              <li class="uk-nav-divider"></li>
              <li><router-link to="#">Career Services</router-link></li>
              <li><router-link to="#">Computer Labs</router-link></li>
            </ul>
        </div>
    </li>
    <li>
        <a href="#">Give<span class="" uk-icon="icon: triangle-down"></span></a>
        <div uk-dropdown="mode: hover">
            <ul class="uk-nav uk-dropdown-nav">
              <li class="uk-active"><router-link to="#">Donate to BRHS</router-link></li>
            </ul>
        </div>
    </li>
</ul>

</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
</style>
