<template>
  <v-card color="info" dark :height='$store.state.homeComponentHeight'>
    <v-card-text
      class="headline font-weight-bold"
    >"Best food in Myanmar chosen by a Myanmar Specialty in Food. Taste one bite and go to heaven without needing to die. I asure you will seek for us again"</v-card-text>

    <v-card-actions>
      <v-list-tile class="grow">
        <v-list-tile-avatar color="grey darken-3">
          <v-img
            class="elevation-6"
            src="https://avataaars.io/?avatarStyle=Transparent&topType=ShortHairShortCurly&accessoriesType=Prescription02&hairColor=Black&facialHairType=Blank&clotheType=Hoodie&clotheColor=White&eyeType=Default&eyebrowType=DefaultNatural&mouthType=Default&skinColor=Light"
          ></v-img>
        </v-list-tile-avatar>

        <v-list-tile-content>
          <v-list-tile-title>Zhon Ke</v-list-tile-title>
        </v-list-tile-content>

        <v-layout align-center justify-end>The Real Fatty</v-layout>
      </v-list-tile>
    </v-card-actions>
  </v-card>
</template>