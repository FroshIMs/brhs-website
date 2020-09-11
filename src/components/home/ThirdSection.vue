<template>

  <div class="uk-child-width-1-2@s uk-margin-bottom" uk-grid>
    <div>
      <BrhsExperience />
    </div>
    <div>
      <Announcements />
    </div>
  </div>

</template>

<script>

import BrhsExperience from '@/components/home/BrhsExperience'
import Announcements from '@/components/home/Announcements'
export default {
name: "ThirdSection.vue",
  components: {Announcements, BrhsExperience}
}
</script>

<style scoped>

</style>
