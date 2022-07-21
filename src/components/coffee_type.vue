<template>
  <v-container fluid class="pa-0" style="background-color: white">
    <v-row justify="center" align="center" class="pt-10">
      <v-card
        v-for="cafe in coffee"
        :key="cafe.index"
        elevation="0"
        class="mx-auto"
        max-width="344"
      >
        <v-img class="rounded-xl" :src="`${cafe.img}`" height="300px"></v-img>

        <v-card-title class="font-weight-bold px-0">
          {{ cafe.name }}
        </v-card-title>

        <v-card-subtitle class="px-0 font-weight-light subtitle-1">
          {{ cafe.subtitle }}
        </v-card-subtitle>
      </v-card>
    </v-row>
    <v-row class="pa-7" justify="end" align="end">
      <v-btn large color="#9E694B" class="text-capitalize white--text"
        ><div class="font-weight-bold pr-2" style="font-size: 15px">More</div>
        <v-icon size="20px">mdi-chevron-double-right</v-icon>
      </v-btn>
    </v-row>
    <v-row justify="center" align="center">
      <v-col cols="5">
        <v-divider></v-divider>
      </v-col>
      <v-col cols="1">
        <img src="../assets/logo.png" width="100px" alt="" />
      </v-col>
      <v-col cols="5">
        <v-divider></v-divider>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    coffee: [
      {
        name: "Americano",
        img: require("@/assets/type/americano.jpg"),
        subtitle:
          "With a similar flavor to black coffee, the americano consists of an espresso shot diluted in hot water. Pro tip: if you’re making your own, pour the espresso first, then add the hot water.",
      },
      {
        name: "Cappucino",
        img: require("@/assets/type/cappucino.jpg"),
        subtitle:
          "Cappuccino is a latte made with more foam than steamed milk, often with a sprinkle of cocoa powder or cinnamon on top. Sometimes you can find variations.",
      },
      {
        name: "Espresso",
        img: require("@/assets/type/espresso.jpg"),
        subtitle:
          "An espresso shot can be served solo or used as the foundation of most coffee drinks, like lattes and macchiatos.",
      },
    ],
  }),
};
</script>

<style lang="scss" scoped>
</style>