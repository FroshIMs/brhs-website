<template>
  <div>
    <h3 class="uk-heading">Announcements</h3>
    <div class="uk-dark uk-background-muted uk-padding">
      <div uk-slider="autoplay: true">
        <div uk-slider="center: false">

          <div class="uk-position-relative uk-visible-toggle uk-light" tabindex="-3">

            <ul class="uk-slider-items uk-child-width-1-2@s uk-grid">
              <li>
                <div class="uk-card">
                  <div class="uk-card-media-top">
                    <img src="https://getuikit.com/docs/images/photo.jpg" alt="">
                  </div>
                  <div class="uk-card-body">
                    <h3 class="uk-card-title">Headline</h3>
                  </div>
                </div>
              </li>
              <li>
                <div class="uk-card">
                  <div class="uk-card-media-top">
                    <img src="https://getuikit.com/docs/images/dark.jpg" alt="">
                  </div>
                  <div class="uk-card-body">
                    <h3 class="uk-card-title">Headline</h3>
                  </div>
                </div>
              </li>
              <li>
                <div class="uk-card">
                  <div class="uk-card-media-top">
                    <img src="https://getuikit.com/docs/images/light.jpg" alt="">
                  </div>
                  <div class="uk-card-body">
                    <h3 class="uk-card-title">Headline</h3>
                  </div>
                </div>
              </li>
              <li>
                <div class="uk-card">
                  <div class="uk-card-media-top">
                    <img src="https://getuikit.com/docs/images/photo2.jpg" alt="">
                  </div>
                  <div class="uk-card-body">
                    <h3 class="uk-card-title">Headline</h3>
                  </div>
                </div>
              </li>
              <li>
                <div class="uk-card">
                  <div class="uk-card-media-top">
                    <img src="https://getuikit.com/docs/images/photo3.jpg" alt="">
                  </div>
                  <div class="uk-card-body">
                    <h3 class="uk-card-title">Headline</h3>
                  </div>
                </div>
              </li>
            </ul>

            <a class="uk-position-center-left uk-position-small uk-hidden-hover" href="#" uk-slidenav-previous uk-slider-item="previous"></a>
            <a class="uk-position-center-right uk-position-small uk-hidden-hover" href="#" uk-slidenav-next uk-slider-item="next"></a>

          </div>

          <ul class="uk-slider-nav uk-dotnav uk-flex-center uk-margin"></ul>

        </div>
      </div>
      </div>
  </div>
</template>

<script>
export default {
name: "Announcements.vue"
}
</script>

<style scoped>

</style>
