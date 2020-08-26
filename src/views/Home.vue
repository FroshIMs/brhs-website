<template>
  <div class="">
    <AppCarousel />
    <div class="my-container">
      <div class="uk-container uk-section uk-section-default">
      <div class="uk-container">

          <h3>Section Default</h3>

          <div class="uk-grid-match uk-child-width-1-3@m" uk-grid>
              <div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
              </div>
              <div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
              </div>
              <div>
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
              </div>
          </div>

      </div>
  </div>

  <div class="uk-margin-bottom">
    <div class="uk-child-width-1-2@s" uk-grid>
      <div>
          <div class="uk-light uk-background-secondary uk-padding">
              <h3>Light</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
              <button class="uk-button uk-button-default">Button</button>
          </div>
      </div>
      <div>
          <div class="uk-dark uk-background-muted uk-padding">
              <h3>Dark</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
              <button class="uk-button uk-button-default">Button</button>
          </div>
      </div>
  </div>
  </div>

    <div class="uk-margin-bottom">
      <div class="uk-section-default">
          <div class="uk-section uk-light uk-background-cover" style="background-image: url(https://getuikit.com/docs/images/dark.jpg)">
              <div class="uk-container">

                  <h3>Section with Images</h3>

                  <div class="uk-grid-match uk-child-width-1-3@m" uk-grid>
                      <div>
                          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
                      </div>
                      <div>
                          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
                      </div>
                      <div>
                          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
                      </div>
                  </div>

              </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AppCarousel from '@/components/AppCarousel'

export default {
  name: 'Home',
  components: {
    AppCarousel
  }
}
</script>

<style>
  .my-container {
    margin-left: 2rem;
    margin-right: 2rem;
  }
</style>
