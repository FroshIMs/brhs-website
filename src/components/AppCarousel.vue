<template lang="html">
  <div uk-slideshow="autoplay: true">
    <div class="uk-position-relative uk-visible-toggle uk-light" tabindex="-1" uk-slideshow="ratio: 7:3; animation: push">

    <ul class="uk-slideshow-items">
        <li>
          <img src="http://www.jamalco.com/jamalco/img/home/slideshow/slide_01.jpg" alt="" uk-cover>
          <div class="uk-overlay uk-overlay-default uk-light uk-position-center">
            <h1 style="color: #008000">Welcome to Jamalco</h1>
          </div>
        </li>
        <li>
          <img src="http://www.jamalco.com/jamalco/img/home/slideshow/slide_02.jpg" alt="" uk-cover>
          <div class="uk-overlay uk-overlay-default uk-light uk-position-bottom">
            <h1 style="color: #008000">From the ground up</h1>
          </div>
        </li>
        <li>
          <img src="http://www.jamalco.com/jamalco/img/home/slideshow/slide_03.jpg" alt="" uk-cover>
          <div class="uk-overlay uk-overlay-default uk-light uk-position-bottom">
            <h1 style="color: #008000">Welcome to Jamalco</h1>
          </div>
        </li>
        <li>
          <img src="http://www.jamalco.com/jamalco/img/home/slideshow/slide_04.jpg" alt="" uk-cover>
          <div class="uk-overlay uk-overlay-default uk-light uk-position-left-center">
            <h1 style="color: #008000">Welcome to Jamalco</h1>
          </div>
        </li>
        <li>
          <img src="http://www.jamalco.com/jamalco/img/home/slideshow/slide_05.jpg" alt="" uk-cover>
          <div class="uk-overlay uk-overlay-default uk-light uk-position-center">
            <h1 style="color: #008000">Welcome to Jamalco</h1>
          </div>
        </li>
        <li>
          <img src="http://www.jamalco.com/jamalco/img/home/slideshow/slide_06.jpg" alt="" uk-cover>
          <div class="uk-overlay uk-overlay-default uk-light uk-position-top-center">
            <h1 style="color: #008000">Welcome to Jamalco</h1>
          </div>
        </li>
        <li>
          <img src="http://www.jamalco.com/jamalco/img/home/slideshow/slide_07.jpg" alt="" uk-cover>
          <div class="uk-overlay uk-overlay-default uk-light uk-position-bottom-center">
            <h1 style="color: #008000">Welcome to Jamalco</h1>
          </div>
        </li>
        <li>
          <img src="http://www.jamalco.com/jamalco/img/home/slideshow/slide_08.jpg" alt="" uk-cover>
          <div class="uk-overlay uk-overlay-default uk-light uk-position-center">
            <h1 style="color: #008000">Welcome to Jamalco</h1>
          </div>
        </li>
    </ul>

    <a class="uk-position-center-left uk-position-small uk-hidden-hover" href="#" uk-slidenav-previous uk-slideshow-item="previous"></a>
    <a class="uk-position-center-right uk-position-small uk-hidden-hover" href="#" uk-slidenav-next uk-slideshow-item="next"></a>

    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>

@media screen and (min-width: 1053px) {
  .uk-overlay {visibility: visible;}
}

@media screen and (max-width: 1052px) {
  .uk-overlay {display: none;}
}
</style>
