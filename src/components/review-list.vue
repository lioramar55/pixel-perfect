<template>
  <div class="review-list">
    <review-preview
      v-for="review in reviews"
      :key="review.id"
      :review="review"
    />
  </div>
</template>

<script>
import reviewPreview from './review-preview.vue'
export default {
  name: 'review-list',
  components: {
    reviewPreview,
  },
  data() {
    return {
      reviews: [
        {
          id: 'r101',
          from: {
            fullname: 'Satish Patel',
            role: 'Founder & CEO, Huddle',
            img: '@/assets/profile-1.jpg',
          },
          content:
            'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.',
        },
        {
          id: 'r102',
          from: {
            fullname: 'Bruce McKenzie',
            role: 'Founder & CEO, Huddle',
            img: '@/assets/profile-2.jpg',
          },
          content:
            'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.',
        },
        {
          id: 'r103',
          from: {
            fullname: 'Iva Boyd',
            role: 'Founder & CEO, Huddle',
            img: '@/assets/profile-3.jpg',
          },
          content:
            'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.',
        },
      ],
    }
  },
}
</script>
