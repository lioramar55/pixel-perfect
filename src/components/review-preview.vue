<template>
  <div class="review-preview">
    <div class="content">
      <p>{{ review.content }}</p>
    </div>
    <div class="from">
      <div class="img">
        <img :src="review.from.img" />
      </div>
      <div class="person">
        <h2>{{ review.from.fullname }}</h2>
        <h3>{{ review.from.role }}</h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'review-preview',
  props: {
    review: Object,
  },
}
</script>
