<template>
  <div class="">
    <AppCarousel />
    <div class="my-container">

      <div class="uk-margin-top uk-margin-bottom">
        <div  uk-scrollspy="target: > div; cls: uk-animation-fade; delay: 500" class="uk-child-width-1-3@m uk-grid-small uk-grid-match" uk-grid>
          <div>
            <div class="uk-card uk-card-default uk-card-body uk-card-hover">
              <h3 class="uk-card-title"><router-link to="#">News</router-link></h3>
              <div>
                <ul class="uk-list uk-text-truncate">
                  <li><a href="pdf/Jamalco%20Donates%20Computers%20to%20Schools.pdf" target=_blank>Jamalco Donates Computers to Schools</a></li>
                  <li><a href="pdf/Jamalco_Press_Release_20200311.pdf" target=_blank>General Alumina Jamaica Limited And Clarendon Alumina Production Limited Reach Agreement On Jamalco Reorganization</a></li>
                  <li><a href="pdf/Jamalco%20launches%202020%20Volunteer%20Programme%20and%20cheque%20Presentation%20to%20Benficiaries.pdf" target=_blank>Jamalco launches 2020 Volunteer Programme and cheque Presentation to Benficiaries</a></li>
                  <li><a href="pdf/Jamalco%20Observes%20Earthquake%20Preparedness%20in%20local%20schools.pdf" target=_blank>Jamalco Observes Earthquake Preparedness in local schools</a></li>
                  <li><a href="pdf/Jamalco%20uses%20health%20and%20fitness%20to%20strengthen%20local%20institutions.pdf" target=_blank>Jamalco uses health and fitness to strengthen local institutions</a></li>
                  <li><a href="pdf/Garvey%20Maceo%20High%20Gets%20J$1-m%20Technology%20Boost%20from%20Jamalco.pdf" target=_blank>Garvey Maceo High Gets $1-m Technology Boost from Jamalco</a></li>
                  <li><a href="pdf/Jamalco%20Awards%20Close%20to%20J$12-m%20in%20Scholarships%20and%20Grants.pdf" target=_blank>Jamalco Awards Close to $12 Million in Scholarships and Grants</a></li>
                </ul>
              </div>
            </div>
          </div>
          <div>
            <div class="uk-card uk-card-default uk-card-body uk-card-hover">
              <h3 class="uk-card-title"><router-link to="#">About Us</router-link></h3>
              <div>
                <p>Jamalco is a joint venture between Noble Group and Clarendon Alumina Production (CAP) with a focus on bauxite mining and alumina production.</p>
              </div>
            </div>
          </div>
          <div>
            <div class="uk-card uk-card-default uk-card-body uk-card-hover">
              <h3 class="uk-card-title"><router-link to="#">Responsibility</router-link></h3>
              <div>
                <p>We are committed to leading practices on environmental performance and energy efficiency, as well as the highest standards of safety, while growing returns for our shareowners, employees, customers, suppliers and Jamaica. </p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="uk-text-center">
        <div uk-grid uk-scrollspy="cls: uk-animation-slide-bottom; target: .uk-card; delay: 300;" class="uk-child-width-1-3@m uk-grid-small uk-grid-match" uk-grid>
          <div>
            <div class="uk-card">
              <div class="uk-inline">
                <img src="http://www.jamalco.com/jamalco/img/home/blocks/responsibility_60_over.jpg" alt="">
                <div class="uk-overlay uk-position-bottom uk-light">
                  <p>Default Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
              </div>
            </div>
          </div>
          <div uk-scrollspy-class="uk-animation-slide-top">
            <div class="uk-card ">
              <div class="uk-inline">
                <img src="http://www.jamalco.com/jamalco/img/home/blocks/aboutus_60_over.jpg" alt="">
                <div class="uk-overlay uk-position-bottom uk-light">
                  <p>Default Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
              </div>
            </div>
          </div>
          <div>
            <div class="uk-card">
              <div class="uk-inline">
                <img src="http://www.jamalco.com/jamalco/img/home/blocks/news_60.jpg" alt="">
                <div class="uk-overlay uk-position-bottom uk-light">
                  <p>Default Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
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
  },
  mounted () {
    window.scrollTo(0, 0)
  }
}
</script>

<style scoped>

</style>
