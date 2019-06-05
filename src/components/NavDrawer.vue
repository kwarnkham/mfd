<template>
  <v-navigation-drawer app clipped v-model="showDrawer" width=200>
    <v-list>
      <v-list-tile v-for="item in items" :key="item.title">
        <v-list-tile-action>
          <v-icon>{{ item.icon }}</v-icon>
        </v-list-tile-action>

        <v-list-tile-content>
          <v-list-tile-title>{{ item.title }}</v-list-tile-title>
        </v-list-tile-content>
      </v-list-tile>
    </v-list>
  </v-navigation-drawer>
</template>

<script>
export default {
  name: "NavDrawer",
  data() {
    return {
      items: [
        { title: "Dashboard", icon: "dashboard" },
        { title: "Account", icon: "account_box" },
        { title: "Admin", icon: "gavel" }
      ],
      showDrawer: null
    };
  },
  methods:{
      toggleShowDrawer(){
          this.showDrawer = !this.showDrawer
          console.log('hi from nav')
      }
  }
};
</script>

<style>
</style>
