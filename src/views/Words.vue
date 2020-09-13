<template>
  <v-container grid-list-xl>
    <v-layout text-center wrap>
      <v-flex xs12>
        <v-card>
          <v-card-title>
            <h1 class="display-1"></h1>
          </v-card-title>

          <v-card-text>
            <h1 class="display-2">Here are some messages for you!</h1>
            <br/>
            <p class="body-2">
              I wish you get everything you desire <br>
              May god bless you and your loved ones <br>
              May your smile be just like this always as it is in those photos <br>
              May your this year becomes more fun and adventurous <br>
              Wishing you a Many Many Happy returns of the day <br></p>

          </v-card-text>
        </v-card>
      </v-flex>

      <v-flex xs12>
        <v-img :src="require('../assets/bday-112.gif')" contain height="200"></v-img>
      </v-flex>

      <v-flex xs12>
        <v-btn to="/" color="info">Back to Home</v-btn>
      </v-flex>
    </v-layout>
  </v-container>
</template>
