<template>
  <div>
    <NavDrawer ref="navDrawer"/>
    <v-toolbar app clipped-left>
      <v-icon class="pr-3 hidden-md-and-up" @click="toggleNavDrawer">menu</v-icon>
      <span class="font-weight-light">Myanmar Specialty Food</span>
      <v-icon color="orange" class="pl-2">fastfood</v-icon>
      <v-spacer></v-spacer>
      <v-icon color="green darken-2" class="pr-2">phone</v-icon>
      <span class="font-weight-light">911</span>
    </v-toolbar>
  </div>
</template>

<script>
import NavDrawer from "@/components/NavDrawer";
export default {
  name: "Toolbar",
  components: {
    NavDrawer
  },
  methods:{
    toggleNavDrawer(){
      this.$refs.navDrawer.toggleShowDrawer()
    }
  }
};
</script>

<style>
</style>
