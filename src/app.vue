<template>
  <div class="app-container">
    <main-header />
    <home-page />
    <main-footer />
  </div>
</template>

<script>
import mainHeader from '@/components/main-header.vue'
import homePage from '@/views/home-page.vue'
import mainFooter from '@/components/main-footer.vue'

export default {
  name: 'app',
  components: {
    mainHeader,
    mainFooter,
    homePage,
  },
}
</script>
