<template>
  <div class="my-container">
    <h3 class="uk-card-title uk-text-bold">Contact Us</h3>
    <div class="uk-child-width-1-3@m uk-grid-small uk-grid-match" uk-grid>
      <div>
        <div class="uk-card">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15186.588848706842!2d-77.24283077452864!3d17.901942341193635!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8edb9c2cceb1eac5%3A0x734c69d5f8c254a2!2sJAMALCO!5e0!3m2!1sen!2sus!4v1597765625700!5m2!1sen!2sus" class="uk-margin-right" max-width="400" height="230" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
        </div>
      </div>
      <div>
        <div class="uk-card uk-card-body">
          <h3 class="uk-card-title">Office</h3>
          <ul class="uk-list uk-list-collapse">
            <li>Kingston</li>
            <li>1st Floor, Citibank Building</li>
            <li>19 Hillcrest Avenue</li>
            <li>Kingston 6</li>
            <li>Jamaica W. I</li>
            <li>Email: <a href="mailto:corporate.services@jamalco.com">corporate.services@jamalco.com</a></li>
            <li>Tel:+1 876 926 3390-5</li>
          </ul>
        </div>
      </div>
      <div>
        <div class="uk-card uk-card-body">
          <h3 class="uk-card-title">Refinery</h3>
          <ul class="uk-list uk-list-collapse">
            <li>Clarendon Alumina Works</li>
            <li>Halse Hall, Clarendon</li>
            <li>Jamaica W. I</li>
            <li>PO Box 64</li>
            <li>May Pen, Clarendon</li>
            <li>Jamaica W. I</li>
            <li>Email: <a href="mailto:corporate.services@jamalco.com">corporate.services@jamalco.com</a></li>
            <li>Tel: +1 876 986 2561-4</li>
            <li>Fax: +1 876 986 2026/9637</li>
          </ul>
        </div>
      </div>
    </div>
    <hr>
    <div class="uk-card uk-background-muted uk-card-body uk-align-center">
      <div class="uk-container uk-border-rounded">
        <h3 class="uk-card-title">Frequently Asked Questions</h3>
        <p>Find here the answers to the most frequently asked questions.</p>
        <ul uk-accordion>
          <li class="uk-open">
            <a class="uk-accordion-title" uk-tooltip="Click to view answer; pos: top-left" href="#">Opportunities</a>
            <div class="uk-accordion-content">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </div>
          </li>
          <li>
            <a class="uk-accordion-title" uk-tooltip="Click to view answer; pos: top-left" href="#">Minning</a>
            <div class="uk-accordion-content">
              <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor reprehenderit.</p>
            </div>
          </li>
          <li>
            <a class="uk-accordion-title" uk-tooltip="Click to view answer; pos: top-left" href="#">Procurement</a>
            <div class="uk-accordion-content">
              <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat proident.</p>
            </div>
          </li>
        </ul>
      </div>
    </div>
    <hr>
    <div class="uk-card uk-background-default uk-card-body uk-align-center">
      <div class="uk-container uk-border-rounded">
        <h3 class="uk-card-title">Did not see your question?</h3>
        <p>Send us a message, we are always happy to hear from you.</p>
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