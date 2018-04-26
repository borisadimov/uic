<template>
  <v-container>
    <v-layout row wrap>
      <v-flex xs12 class="cards">
        <img src="img/cards.png" class="home-card">
      </v-flex>
      <v-flex xs12>
        <h1>Welcome</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing</p>
        <v-btn class="get-started" large round>Get Started</v-btn>
      </v-flex>
      <v-flex xs12>
        <a href="" class="login">Log In</a>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<style lang="stylus">
.home-card
  width 281px
  display inherit
  margin 70px auto 0 auto

.cards
  background url('/img/bubbles.png') no-repeat center
  background-size 326px
  margin 0 auto

h1
  font-size 30px
  text-align center
  font-family 'Zilla Slab', serif
  color rgba(255,255,255,1)
  margin 1rem 0

p
  text-align center
  font-size 19px
  color rgba(255,255,255,0.7)

.btn
  margin 0 auto
  display table

.get-started
  background-color #278ab5 !important
  border-radius 100px
  font-family 'Zilla Slab', serif
  letter-spacing 1px
  margin-top 30px

.login
  font-size 18px
  text-decoration underline
  color rgba(255,255,255,0.7)
  text-align center
  display inherit
  text-align center
  margin-top 60px
</style>
