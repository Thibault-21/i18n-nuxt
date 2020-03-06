<template>
  <div class="container">
    <h1>Welcome to test - index page</h1>
    <h1>test i18n </h1>
    <nuxt />
  </div>
</template>

<script>
import about from '../pages/about'
import blog from '../pages/blog.vue'
import contact from '../pages/contact.vue'

export default {
  layout: 'default',
  components: {
    about,
    blog,
    contact
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
