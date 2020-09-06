<template lang="html">
  <div class="uk-margin-large-top">
    <div class="uk-section uk-section-default">
      <hr>
      <div class="uk-container">

        <div class="uk-margin-left">

          <div class="uk-child-width-1-3@m uk-grid-small uk-grid-match" uk-grid>
            <div>
              <div class="uk-card uk-card-body">
                <h3 class="uk-card-title">Get to know Jamalco</h3>
                <ul class="uk-list">
                  <li><router-link :to="{ name: 'Home'}">Home</router-link></li>
                  <li><router-link :to="{ name: 'About'}">About Us</router-link></li>
                  <li><router-link :to="{ name: 'Contact'}">Contact Us</router-link></li>
                  <li><router-link :to="{ name: 'TermsOfUse'}">Terms of Use</router-link></li>
                </ul>
              </div>
            </div>
            <div>
              <div class="uk-card uk-card-body">
                <h3 class="uk-card-title">About Jamalco</h3>
                <ul class="uk-list">
                  <li><router-link :to="{ name: 'News'}">News</router-link></li>
                  <li><router-link :to="{ name: 'Careers'}">Careers</router-link></li>
                  <li><router-link :to="{ name: 'Community'}">Community</router-link></li>
                  <li><router-link :to="{ name: 'Responsibility'}">Responsibility</router-link></li>
                  <li><router-link :to="{ name: 'AluminaIndustry'}">Alumina Industry</router-link></li>
                </ul>
              </div>
            </div>
            <div>
              <div class="uk-card uk-card-body">
                <h3 class="uk-card-title">Connect with Jamalco</h3>
                <a href="" class="uk-icon-button uk-margin-small-right" uk-icon="twitter"></a>
                <a href="" class="uk-icon-button uk-margin-small-right" uk-icon="instagram"></a>
                <a href="" class="uk-icon-button uk-margin-small-right" uk-icon="facebook"></a>
                <a href="" class="uk-icon-button uk-margin-small-right" uk-icon="linkedin"></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="uk-text-center">
      <hr>
      <p>&copy; Jamalco 2020. All Rights Reserved.</p>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>

</style>
