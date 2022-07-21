<template>
  <v-container fluid class="pa-0">
    <hello-world />
    <info />
    <Coffee_type />
    <subscribe />
    <Footer />
  </v-container>
</template>

<script>
import Coffee_type from "../components/coffee_type.vue";
import Footer from "../components/footer.vue";
import HelloWorld from "../components/HelloWorld";
import info from "../components/info";
import Subscribe from "../components/subscribe.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    info,
    Coffee_type,
    Subscribe,
    Footer,
  },
};
</script>
<style>
</style>
