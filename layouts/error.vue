<template>
  <div class="container">
    <h1 v-if="error.statusCode === 404">Page not found {{error.statusCode}}</h1>
    <h2>{{error.message}}</h2>
    <NuxtLink to="/">Home page</NuxtLink>
  </div>
</template>

<script>
export default {
  props: ['error'],
  layout: 'default' // you can set a custom layout for the error page
}
</script>
