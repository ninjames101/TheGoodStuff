<template>
  <div id="landing">
  <v-layout>
    <v-flex xs12 sm6 offset-sm3>
      <v-card id="me">

        <v-card-title>
            <h3 class="pl-3">Hey! You found "The Good Stuff"</h3>
        </v-card-title>
        <v-card-text>
          <h6 class="text-xs-center">Click on one of the links above to get some</h6>
            </v-card-text>

      </v-card>
    </v-flex>
  </v-layout>
    <v-parallax src="/static/fam2.jpg" height="1000"></v-parallax>
<v-layout>
  <v-flex  xs3>
    <v-card id="contact" class="elevation-5">
    <v-card-title>
    <h3 class="text-xs-center">LinkedIn</h3>
  </v-card-title>
  <v-card-text>
    <h6>/ninjames101</h6>
  </v-card-text>

    </v-card>
  </v-flex>
  <v-flex  xs3>
    <v-card id="contact" class="elevation-5">
    <v-card-title>
    <h3 class="text-xs-center">GitHub</h3>
  </v-card-title>
  <v-card-text>
    <h6>/ninjames101</h6>
  </v-card-text>

    </v-card>
  </v-flex>
  <v-flex  xs3>
    <v-card id="contact" class="elevation-5">
    <v-card-title>
    <h3 class="text-xs-center">Youtube</h3>
  </v-card-title>
  <v-card-text><h6> search "ninjames"</h6>
  </v-card-text>

    </v-card>
  </v-flex>
  <v-flex  xs3>
    <v-card id="contact" class="elevation-5">
    <v-card-title>
    <h3 class="text-xs-center">Website</h3>
  </v-card-title>
  <v-card-text>
    <h6>www.ninjames101.ninja</h6>
  </v-card-text>

    </v-card>
  </v-flex>
  </v-layout>







  </div>
</template>

<script>
export default {
name: 'landing',
data () {
  return {

  }
}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#me {
  background-color: #F2EFEA;
}
h3, h6 {
  /*color: #20BF55;*/
  color: #FF8A65;
}


</style>
