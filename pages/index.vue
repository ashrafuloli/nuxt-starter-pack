<template>
  <NuxtLayout>
    <HomeOne></HomeOne>
  </NuxtLayout>
</template>

<script>
import HomeOne from "~/components/HomeOne/HomeOne.vue";

export default {
  name: 'IndexPage',
  components: {HomeOne},
  layout: 'default',
}
</script>
