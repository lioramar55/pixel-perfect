<template>
  <div class="get-started">
    <div class="dark-spacer"></div>
    <div class="get-started-form">
      <h1>Get early access today</h1>
      <p>
        It only takes a minute to sign up and our free
        starter tier is extremely generous. If you have any
        questions, our support team would be happy to help
        you.
      </p>
      <form @submit.prevent="submit">
        <input
          type="email"
          placeholder="email@example.com"
        />
        <button>Get Started For Free</button>
      </form>
    </div>
    <div class="spacer"></div>
  </div>
</template>

<script>
export default {
  name: 'get-started',
}
</script>
