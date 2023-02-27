<template>
  <div>
    <Header></Header>
    <Nuxt/>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "~/components/Header/Header.vue";
import Footer from "~/components/Footer/Footer.vue";

export default {
  name: "default.vue",
  components: {Footer, Header}
}
</script>

<style scoped>

</style>
