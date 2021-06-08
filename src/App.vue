<template>
  <v-app>
      <v-row>
        <v-col md="12">
        <v-card>
          <v-tabs
              v-model="tab"
              background-color="deep-purple accent-4"
              centered
              dark
              icons-and-text
          >
            <v-tabs-slider></v-tabs-slider>

            <v-tab :key="1">
              Memes
              <v-img src="../Img/Bar.png"></v-img>
            </v-tab>

            <v-tab :key="2">
              Беды с бошкой
              <v-img src="../Img/bedasbashkoy_stick.png"></v-img>
            </v-tab>

            <v-tab :key="3">
              Спрятался
              <v-icon>corovovirus</v-icon>
            </v-tab>
            <v-tab-item :key="1" ><memes></memes></v-tab-item>
            <v-tab-item :key="2">
              <v-img src="../Img/arthas_orex.png"> </v-img>
            </v-tab-item>
            <v-tab-item :key="3"> <v-img src="../Img/solid_cow_stick.png"> </v-img> </v-tab-item>
          </v-tabs>
        </v-card>
        </v-col>
      </v-row>

  </v-app>
</template>

<script>
import memes from '../src/views/memes';
export default {
  name: 'App',

  components: {
  memes
  },

  data: () => ({
    item:memes
  }),
};
</script>

<style>
body {
  background-image: url("../Img/Bar.png") !important;
}
</style>
