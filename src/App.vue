<template>
  <v-app>
    <v-main>
      <app-bar />
      <router-view v-slot="slotProps">
        <transition name="route" mode="out-in">
          <component :is="slotProps.Component"></component>
        </transition>
        </router-view>
    </v-main>
  </v-app>
</template>

<script>
import appBar from "./components/appBar.vue";
export default {
  components: {
    appBar,
  },
  name: "App",
  data: () => ({
    //
  }),
};
</script>

<style>
/* .route-enter-from{

} */

.route-enter-acitve {
  animation: slide-scale 0.4s ease-out;
}
/* .route-enter-to{

} */

.route-leave-active {
  animation: slide-scale 0.4s ease-in;
}
</style>
