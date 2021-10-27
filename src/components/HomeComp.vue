<template>
  <div class="home">
    <v-parallax src="@/assets/home.jpeg">
      <div
        class="heading black--text"
        style="
          text-align: center;
          font-family: 'Yanone Kaffeesatz', sans-serif;
          font-size: 50px;
          letter-spacing: 15px;
        "
      >
        hello, there. <br />
        I'M BABY AYU
      </div>
      <div
        class="subheading font-weight-regular black--text ma-20"
        style="
          text-align: center;
          font-family: 'Signika Negative', sans-serif;
          font-size: 25px;
        "
        xs8
      >
        Below are some of bidding projects I've worked on.
        <br />
        Thanks for stopping by!
        <br />
        Read more, here.
        <br />
        <v-btn rounded class="black--text" href="#challenge"
          >GET STARTED
        </v-btn>
      </div>
    </v-parallax>

    <section id="challenge">
      <Challenge />
    </section>
    <Footer />
  </div>
</template>

<script>
import Challenge from "./Challenge.vue";
import Footer from "./Footer.vue";

export default {
  name: "Home",
  components: {
    Challenge,
    Footer,
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Festive&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Festive&family=Raleway:wght@600&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Festive&family=Raleway:wght@600&family=Yanone+Kaffeesatz&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Festive&family=Raleway:wght@600&family=Signika+Negative&family=Yanone+Kaffeesatz&display=swap");
</style>