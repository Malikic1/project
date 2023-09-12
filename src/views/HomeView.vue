<template>
  <main>
    <LandingPage />
  </main>
</template>

<script>
import LandingPage from "@/components/LandingPage.vue";

export default {
  name: "HomeView",
  components: {
    LandingPage,
  },
};
</script>
<style>
main {
  padding: 10px 5% 10px 5%;
}
</style>
