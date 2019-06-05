<template>
  <v-app class="grey lighten-2">
    <Toolbar/>
    <v-content>
      <v-container fluid class="ma-0 pa-0">
        <router-view></router-view>
      </v-container>
    </v-content>
    <v-footer app dark class="d-flex">
      <span class="text-xs-center">
        &copy;2019 —
        <strong>Myanmar Specialty Food</strong>
      </span>
    </v-footer>
  </v-app>
</template>

<script>
import Toolbar from "@/components/Toolbar";
export default {
  name: "App",
  components: {
    Toolbar
  },
  data() {
    return {
      //
    };
  }
};
</script>
