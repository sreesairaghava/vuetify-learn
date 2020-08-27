<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <v-btn round color="primary" dark to="/">Sree Sai Raghava</v-btn>
    </v-app-bar>
    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",
  data: () => ({
    //
  })
};
</script>
