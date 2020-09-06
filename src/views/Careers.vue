<template>
  <div class="my-container">
    <h3 class="uk-text-bold uk-text-center">Career Opportunities at Jamalco</h3>

      <div class="uk-section uk-preserve-color">
        <div class="uk-container">

          <div class="uk-grid-match uk-child-width-expand@m" uk-grid>
            <div>
              <h3 class="uk-card-title uk-text-center">Join our team!</h3>
              <div class="uk-card uk-card-default uk-card-body">
                <p>Jamalco offers a wide range of career opportunities within Jamaica and is always in search of diverse, talented people who can contribute and share in our success and commitment to exceed our customers’ expectations. Sustaining this level of performance depends upon fostering a corporate culture where people are passionate about contributing their ideas, interacting with others and taking risks and responsibility. We believe the key to our future is our people.</p>
                <p>Vacancies are advertised here and in the media as they arise.</p>
              </div>
            </div>

            <div>
              <div class="uk-card uk-card-default uk-card-body">
                <div><img src="http://www.jamalco.com/jamalco/img/careers/Careers-DSC_1724.jpg" alt=""></div>
              </div>
            </div>

          </div>

        </div>
      </div>

      <div class="uk-card uk-card-default uk-grid-collapse uk-child-width-1-2@s uk-margin" uk-grid>
        <div class="uk-card-media-left uk-cover-container">
          <img src="http://www.jamalco.com/jamalco/img/careers/Careers-DSC_1729.jpg" alt="" uk-cover>
          <canvas width="600" height="400"></canvas>
        </div>
        <div>
          <div class="uk-card-body">
            <h2 class="uk-card-title">Who do we hire?</h2>
            <p>Jamalco is always on the lookout for high-calibre candidates who fit into our culture of excellence and desire career development and continuous challenge. Our recruits should be willing to live our values and thrive in our corporate culture.</p>
          </div>
        </div>
      </div>

      <div class="uk-flex uk-flex-center">
        <div class="uk-card uk-card-body">
          <h3 class="uk-card-title">Contact us at</h3>
          <p>Email: <a href="mailto:kjwjamalco_hr@jamalco.com">corporate.services@jamalco.com</a></p>
          <div>
            <form class="uk-form-stacked">

              <div class="uk-margin">
                <label class="uk-form-label" for="form-stacked-text">Your name</label>
                <div class="uk-form-controls">
                  <input class="uk-input uk-form-width-large" id="form-stacked-text" type="text" placeholder="example: Jane Doe">
                </div>
              </div>

              <div class="uk-margin">
                <label class="uk-form-label" for="form-stacked-text1">Your email</label>
                <div class="uk-form-controls">
                  <input class="uk-input uk-form-width-large" id="form-stacked-text1" type="text" placeholder="example: janedone@gmail.com">
                </div>
              </div>

              <div class="uk-margin">
                <label class="uk-form-label" for="form-stacked-text2">Your message</label>
                <textarea class="uk-textarea uk-form-width-large" id="form-stacked-text2" rows="5" placeholder="What you would like to say us."></textarea>
              </div>

              <button class="uk-button send-btn">Send</button>

            </form>
          </div>
        </div>
      </div>

  </div>
</template>

<script>
export default {
  mounted () {
    window.scrollTo(0, 0)
  }
}
</script>

<style scoped>
.send-btn {
  background-color: #008000;
  color: #FFFFFF;
}
</style>