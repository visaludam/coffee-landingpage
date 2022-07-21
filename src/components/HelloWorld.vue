<template>
  <v-container fluid class="pa-16 pt-0">
    <v-row class="pa-16 pt-0">
      <v-col cols="12" sm="12" md="9" class="pa-0">
        <div
          class="font"
          style="font-family: 'Red Hat Text', sans-serif; color: #915d47"
        >
          <div style="font-size: 40px" class="font-weight-black">
            Life is too short for bad coffee.
          </div>
          <p class="sub-titile" style="font-size: 25px">
            Coffee literature is full of coffee quotes, quips, and anecdotes.
            They are the product of our passion for coffee, which expresses
            itself as extravagant poetic flights in praise of it.
          </p>
        </div>
      </v-col>
    </v-row>
    <v-row align="start" class="px-16 pt-0">
      <v-col cols="12" md="6">
        <div class="align-center">
          <v-btn x-large style="color: #915d47">
            <span class="font-weight-bold">View </span
            ><span class="font-italic"> Our Products</span></v-btn
          >
        </div>
      </v-col>
      <v-col cols="2" class="pa-0"></v-col>
      <!-- <v-col cols="2" class="pa-0">
        <v-card
          style="background-color: #9d4926; opacity: 0.7; color: white"
          height="300px"
          width="100%"
        >
          <v-card-title
            class="font-italic font-weight-bold justify-end align-end"
            >Arabica</v-card-title
          >
          <v-spacer></v-spacer>
          <v-card-subtitle class="white--text justify-end align-end"
            >Arabica is the most popular type of coffee, hands
            down.</v-card-subtitle
          >
        </v-card>
      </v-col> -->
      <v-col cols="12" md="4" class="py-10">
        <div class="parent">
          <v-img
            src="../assets/background.jpg"
            width="100%"
            max-width="500"
            min-width="250"
            alt=""
          ></v-img>
          <!-- <div class="centered">Center</div> -->
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({}),
};
</script>
<style >
.parent {
  position: relative;
  color: white;
}
.centered {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.image {
  position: relative;
  width: 100%; /* for IE 6 */
}

h2 {
  position: absolute;
  top: 200px;
  left: 0;
  width: 100%;
}

h2 span {
  color: white;
  font: bold 24px/45px Helvetica, Sans-Serif;
  letter-spacing: -1px;
  background: rgb(0, 0, 0); /* fallback color */
  background: rgba(0, 0, 0, 0.7);
  padding: 10px;
}
</style>
