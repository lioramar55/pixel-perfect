<template>
  <div class="benefit-preview">
    <div class="icon">
      <img :src="benefit.img" />
    </div>
    <div class="benefit-title">
      <h2>{{ benefit.title }}</h2>
    </div>
    <div class="benefit-description">
      <p>{{ benefit.description }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'benefit-preview',
  props: {
    benefit: Object,
  },
  created() {
    console.log('this.benefit', this.benefit)
  },
}
</script>
