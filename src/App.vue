<template>
  <v-app id="app">
    <v-container fluid class="pa-16">
      <v-row class="pa-16 pt-0">
        <div class="d-flex align-center" style="color: black">
          <v-icon size="37" color="black">mdi-coffee-outline</v-icon>
          <div class="font" style="font-size: 33px">Koffein</div>
        </div>

        <v-spacer></v-spacer>

        <div class="text-center d-flex">
          <div class="d-flex" style="font-size: 18px">
            <div class="">Home</div>
            <div class="px-5">Contact</div>
            <div class="">Our Products</div>
          </div>
        </div>

        <v-spacer></v-spacer>

        <v-btn
          target="_blank"
          text
          class="hidden-sm-and-down text-capitalize font-weight-regular"
        >
          <v-icon>mdi-arrow-right-thin</v-icon>
          <span class="mr-2" style="font-size: 16px">Sign in</span>
        </v-btn>
      </v-row>
    </v-container>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Nova+Script&family=Red+Hat+Text:wght@300&display=swap");
div.font {
  font-family: "Nova Script", cursive;
}
#app {
  font-family: "Red Hat Text", sans-serif;
  background-color: #edd7bf;
}
</style>
