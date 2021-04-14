<template>
  <section class="container">
    <h1>About our Nuxt WebSite!</h1>
    <p class="subheading">Information about this nuxt.</p>

    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
  </section>
</template>

<script>
export default {
  // transition: 'bounce',
  head() {
    return {
      title: 'About Nuxt',
      meta: [
        { name: 'description', content: 'This is my about description here' },
        { name: 'keywords', content: 'about nuxt, nuxt info' },
      ]
    }
  }
}
</script>

<style>

</style>