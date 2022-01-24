<template>
<div>
  <section id="header">
<v-container fluid class="ma-0 hero">
  <v-row>
    <v-col class="d-flex align-center justify-center flex-column">
      <div class="d-flex align-center justify-center flex-column flex-grow-1">
      <div class="text-h1 font-weight-light pb-3 white--text">jaidyn.</div>
      <p class="text-h4 font-weight-thin white--text text-center">clothing to encourage, edify, and empower.</p>
      </div>
      <p class="text-h4 font-weight-thin white--text my-5">coming soon.</p>
      <div class="my-3 d-flex flex-column flex-md-row space-between">
        <!-- <v-btn color="white" x-large class="ma-2 px-12">SHOP</v-btn>
        <v-btn color="white" x-large outlined class="ma-2 px-8">CONTACT</v-btn> -->
      </div>
    </v-col>
  </v-row>
</v-container>
  </section>
  <!-- <section id="coming-soon" class="my-12">
    <v-container>
      <v-row>
        <v-col>
          <div class="text-h2 text-center">
            <p>coming soon.</p>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </section> -->
</div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style scoped>
.hero {
  background: linear-gradient(to bottom right,rgba(192, 108, 132, 0.7), rgba(108, 91, 123, 0.7), rgba(53, 92, 125, 0.8)); /*url('/img/pexels-trinity-kubassek-341858.jpg');*/
  background-repeat: no-repeat;
  background-size: cover;
  height: 100vh;
  background-position: center bottom;
  display: flex;
    /* -webkit-clip-path: polygon(0 0, 100% 0, 100% 86%, 0 100%);
  clip-path: polygon(0 0, 100% 0, 100% 86%, 0 100%); */
}

</style>
