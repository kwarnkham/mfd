<template>
  <v-layout row wrap justify-space-around>
    <v-flex xs12 sm6 md4>
      <HomeCarousel/>
    </v-flex>
    <v-flex xs12 sm6 md4>
      <HomeAction/>
    </v-flex>
    <v-flex xs12 sm6 md4>
      <TextCard/>
    </v-flex>
  </v-layout>
</template>

<script>
import HomeCarousel from "@/components/HomeCarousel";
import TextCard from "@/components/TextCard";
import HomeAction from "@/components/HomeAction";
export default {
  components: {
    HomeCarousel,
    TextCard,
    HomeAction
  }
};
</script>

<style scoped>
.layout>div{
  padding: 5px;
}
</style>


