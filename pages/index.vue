<template>
  <div class="font-sans bg-gray-200 border-t-8">
    <div class="mt-20 px-10 ">
      <logo />
      <div class="center text-center">
<h1 class="title">
        ssc2020
      </h1>
      <h2 class="subtitle">
        Week 4 OJT Task
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey"
        >
          GitHub
        </a>
        <nuxt-link
          to="/home"
          class="button--grey"
        >
          Proceed to Project
        </nuxt-link>
      </div>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.center {
  margin: auto;
  width: 50%;
  padding: 10px;
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
page-enter-active, .page-leave-active {
      transition: all .30s ease-out;
    }
    .page-enter, .page-leave-active {
      opacity: 0;
      transform-origin: 50% 50%;
    }
</style>
