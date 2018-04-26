<template>
  <v-container grid-list-xl>
    <v-layout row>
      <v-flex>
        <h1>My Courses</h1>
      </v-flex>
    </v-layout>
    <v-layout row wrap>
      <v-flex xs6>
        <v-card class="course">
          <v-card-text class="px-0">Cavity Prevention</v-card-text>
           <v-progress-linear v-model="valueDeterminate"></v-progress-linear>
        </v-card>
      </v-flex>
      <v-flex xs6>
        <v-card class="course">
          <v-card-text class="px-0">Baby Teeth</v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs6>
        <v-card class="course">
          <v-card-text class="px-0">Proper Brushing</v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs6>
        <v-card class="course">
          <v-card-text class="px-0">Prenatal Oral Care</v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs6>
        <v-card class="course">
          <v-card-text class="px-0">Sugary Sweets</v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs6>
        <v-card class="course">
          <v-card-text class="px-0">Home Dental Care</v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>
<script>
  export default {
    data () {
      return {
        valueDeterminate: 50
      }
    }
  }
</script>

<style lang="stylus">
h1
  font-size 30px
  font-family 'Zilla Slab', serif
  color rgba(255,255,255,1)
  margin 1rem 0
  font-weight 700
h2
  font-size 18px
  font-family 'Zilla Slab', serif
  color rgba(255,255,255,1)
  font-weight 700
.course
  background-color: rgba(46, 74, 110, .5) !important
  border-radius: 10px
  min-height: 157px
  box-shadow: none
  padding 15px
.card__text
  font-size 18px
  font-family 'Zilla Slab', serif
  color rgba(255,255,255,1)
  font-weight 700
</style>
