<template>
  <v-app>
    <v-app-bar app color="white" dark>
      <div class="d-flex align-center">
        <v-img
          src="@/assets/jcc.png"
          contain
          transition="scale-transition"
          width="150"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn text>
        <a class="black--text" href="#" style="text-decoration: none">Home</a>
      </v-btn>
      <v-btn text>
        <a class="black--text" href="#challenge" style="text-decoration: none"
          >Challenge</a
        >
      </v-btn>
    </v-app-bar>

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
