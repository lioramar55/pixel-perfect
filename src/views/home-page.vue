<template>
  <div class="home-page">
    <page-hero />
    <benefit-list />
    <stay-productive />
    <review-list />
    <get-started />
  </div>
</template>

<script>
import pageHero from '../components/page-hero.vue'
import benefitList from '../components/benefit-list.vue'
import stayProductive from '../components/stay-productive.vue'
import reviewList from '../components/review-list.vue'
import getStarted from '../components/get-started.vue'

export default {
  name: 'home-page',
  components: {
    pageHero,
    benefitList,
    stayProductive,
    reviewList,
    getStarted,
  },
}
</script>
