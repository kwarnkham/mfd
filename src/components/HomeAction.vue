<template>
  <v-card :height="$store.state.homeComponentHeight" class="teal lighten-1">
    <v-card-title>Quck Actions</v-card-title>
    <v-layout row wrap justify-center align-center>
        <v-flex xs8>We have lot of things to explore</v-flex>
        <v-flex xs4><v-btn>Explore</v-btn></v-flex>
        <v-flex xs8>Just call us! We are happy to help</v-flex>
        <v-flex xs4><v-btn>Call</v-btn></v-flex>
        <v-flex xs8>Can also visit our local shops</v-flex>
        <v-flex xs4><v-btn>Visit</v-btn></v-flex>
        <v-flex xs8>The wait is done. ORDER NOW!</v-flex>
        <v-flex xs4><v-btn>Order</v-btn></v-flex>
    </v-layout>
  </v-card>
</template>

<script>
export default {};
</script>

<style scoped>
.layout>*{
    text-align: center;
}
</style>

