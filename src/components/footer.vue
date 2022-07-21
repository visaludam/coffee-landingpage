<template>
  <v-container fluid class="pa-0" style="background-color: #e2c5a6">
    <v-row justify="center" align="center" style="height: 300px">
      <v-col cols="12" md="6">
        <div class="d-flex justify-space-around" style="font-size: 16px">
          <div>Privacy Policy</div>
          <div>Term & Service</div>
        </div>
        <div class="text-center pt-8">
          <v-icon
            size="35"
            color="#9E694B"
            class="px-4"
            v-for="icon in icons"
            :key="icon.index"
            >{{ icon }}</v-icon
          >
        </div>
      </v-col>
      <v-col class="pt-0" cols="12" md="6">
        <div class="text-center" style="font-size: 16px">
          Made with ❣️☕ | ️koffein-coffee.com <br />
          © Copyright 2020. All rights reserved.
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    icons: [
      "mdi-instagram",
      "mdi-twitch",
      "mdi-twitter",
      "mdi-linkedin",
      "mdi-facebook",
    ],
  }),
};
</script>

<style lang="scss" scoped>
</style>