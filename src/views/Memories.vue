<template>
  <v-container fluid grid-list-xl>
    <v-layout row text-center wrap>
      <v-flex xs12>
        <h1 class="display-3">Memories</h1>
      </v-flex>

      <v-flex xs12 sm6 md4>
        <v-card>
          <v-img :src="require('../assets/1.jpeg')" aspect-ratio="1" ></v-img>
          <v-card-title primary-title>
            <v-card-text>
              <h1 class="headline text-xs-center">Sisters!</h1><br>
              <h2 class="subheading">Lorem ipsum dolor sit amet, consectetur adipiscing elit, \
                sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad \
                minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea \
                commodo consequat.</h2>
            </v-card-text>
          </v-card-title>
        </v-card>
      </v-flex>

      <v-flex xs12 sm6 md4>
        <v-card>
          <v-img :src="require('../assets/2.jpeg')" aspect-ratio="1"></v-img>
          <v-card-title primary-title>
            <v-card-text>
              <h1 class="headline">When I was smol</h1><br>
              <h2 class="subheading">Lorem ipsum dolor sit amet, consectetur adipiscing elit, \
                sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad \
                minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea \
                commodo consequat.</h2>\
            </v-card-text>
          </v-card-title>
        </v-card>
      </v-flex>

      <v-flex xs12 sm6 md4>
        <v-card>
          <v-img :src="require('../assets/3.jpeg')" aspect-ratio="1"></v-img>
          <v-card-title primary-title>
            <v-card-text>
              <h1 class="headline">Felicity</h1><br>
               <h2 class="subheading">Lorem ipsum dolor sit amet, consectetur adipiscing elit, \
                sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad \
                minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea \
                commodo consequat.</h2>
            </v-card-text>
          </v-card-title>
        </v-card>
      </v-flex>

      <v-flex xs12 sm6 md4>
        <v-card>
          <v-img :src="require('../assets/4.jpeg')" aspect-ratio="1.2"></v-img>
          <v-card-title primary-title>
            <v-card-text>
              <h1 class="headline">that smile</h1><br>
               <h2 class="subheading">Lorem ipsum dolor sit amet, consectetur adipiscing elit, \
                sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad \
                minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea \
                commodo consequat.</h2>
            </v-card-text>
          </v-card-title>
        </v-card>
      </v-flex>


      <v-flex xs12>
        <v-img :src="require('../assets/bday-159.gif')" contain height="300"></v-img>
      </v-flex>

      <v-flex xs12>
        <v-btn to="/words" color="info">This is For You</v-btn>
      </v-flex>
    </v-layout>
  </v-container>
</template>
