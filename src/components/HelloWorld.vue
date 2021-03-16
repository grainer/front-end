<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img :src="require('../assets/img/logo.svg')" class="my-3" contain height="200" />
      </v-col>

      <v-col class="mb-4">
        <h1 class="text-5xl font-bold">Welcome to the frontend exersise</h1>
        <p>if you are able to see this, congratulations you are properly setup.</p>
        <p>
          As you may noticed this is a starter kit with our development environment and code
          practices to get you quickly started.
        </p>
        <p>
          this project uses manily
          <a href="https://tailwindcss.com/" class="text-blue-600">Vuetify</a> and
          <a href="https://tailwindcss.com/" class="text-green-600">TailwindCSS</a> and we want you
          to use them.
        </p>
      </v-col>
      <v-col class="mb-5" cols="12">
        <h2 class="headline font-weight-bold mb-3">What's next?</h2>
        <p>Follow the instructions as mentioned in the repo readme</p>
        <h3 class="text-3xl font-bold">All the best!</h3>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator';

@Component({
  name: 'HelloWorld',
})
export default class HelloWorld extends Vue {}
</script>
