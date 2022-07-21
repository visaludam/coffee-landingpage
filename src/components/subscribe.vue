<template>
  <v-container fluid class="pa-0" style="background-color: white">
    <v-row justify="center" align="center">
      <div style="font-size: 22px" class="font-weight-bold grey--text">
        Don't miss our Coffee Update!
        <v-icon size="60" color="#EEDCCA"
          >mdi-email-outline mdi-rotate-315</v-icon
        >
      </div>
    </v-row>
    <v-row justify="center" align="center" class="py-6">
      <div class="text-subtitle text-center px-13">
        Join us by subscribing and get our best coffee news delivered every week
        and month!
      </div>
    </v-row>
    <v-row justify="center" align="center" class="py-5">
      <div>
        <v-card
          height="40px"
          width="100%"
          outlined
          class="d-flex"
          style="border-radius: 50px; background-color: #eaeaea"
        >
          <v-card-title class="pa-0 px-0" style="width: 100%">
            <v-text-field
              class="py-0 grey--text text--darken-3"
              rounded
              dense
              background-color="#EAEAEA"
              placeholder="Email Address"
              style="width: 100%"
              hide-details="true"
            ></v-text-field>
          </v-card-title>
          <v-card-title class="py-0 pr-0">
            <v-btn
              height="38"
              class="white--text font-weight-bold"
              color="#9E694B"
              rounded
              >Subscribe</v-btn
            >
          </v-card-title>
        </v-card>
      </div>
    </v-row>
    <v-row justify="center" align="center" class="pb-10">
      <v-checkbox v-model="checkbox" color="#9E694B"> </v-checkbox>
      <div class="font-italic text-decoration-underline">
        I have read and agree to the term and conditions
      </div>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    checkbox: false,
  }),
};
</script>

<style lang="scss" scoped>
</style>