<template>
  <main class="container">
    <AppHeader />
    <AppRestaurantInfo />
    <!-- <AppFooter /> -->
  </main>
</template>

<script>
import AppHeader from "@/components/AppHeader.vue"
// import AppFooter from "@/components/AppFooter.vue"
import AppRestaurantInfo from "@/components/AppRestaurantInfo.vue"

export default {
  components: {
    AppHeader,
    AppRestaurantInfo,
    // AppFooter,
  },
}
</script>

<style></style>
