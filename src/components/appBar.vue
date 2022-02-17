<template>
  <v-toolbar flat color="transparent" absolute width="100%" dark>
    <router-link to="/" style="text-decoration:none; color:inherit;" >
      <v-toolbar-title dark> Chance Bentulan </v-toolbar-title>
    </router-link>

    <v-spacer></v-spacer>

    <v-btn class="hidden-sm-and-down" text rounded href="#sec-1" > About </v-btn>
    <v-btn class="hidden-sm-and-down" text rounded href="#sec-2">
      Skills
    </v-btn>
    <v-btn class="hidden-sm-and-down" text rounded href="#sec-3"> Contact </v-btn>
  </v-toolbar>
</template>

<script>
export default {
  name: "appBar",
};
</script>
