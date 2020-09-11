<template>
  <div class="">
    <AppCarousel />
    <div class="my-container">

<!--      Featured Stories -->
      <FeaturedStories />
<!--      -->

<!--      Second Section -->
      <SecondSection />
<!--      -->

<!--  Third Section -->
      <ThirdSection />
<!--      -->

<!--    Fourth Section -->
      <FourthSection />
<!--      -->

<!--      Fifth Section -->
      <FifthSection />
<!--      -->

    </div>
  </div>
</template>

<script>
import AppCarousel from '@/components/AppCarousel'
import FeaturedStories from '@/components/home/FeaturedStories'
import SecondSection from '@/components/home/SecondSection'
import ThirdSection from '@/components/home/ThirdSection'
import FourthSection from '@/components/home/FourthSection'
import FifthSection from '@/components/home/FifthSection'

export default {
  name: 'Home',
  components: {
    FifthSection,
    FourthSection,
    ThirdSection,
    SecondSection,
    FeaturedStories,
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
