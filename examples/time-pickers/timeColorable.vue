<template>
  <v-layout row wrap>
    <v-flex md12 lg6>
      <v-time-picker color="green lighten-1" v-model="e4"></v-time-picker>
    </v-flex>
    <v-flex md12 lg6 class="hidden-xs-only">
      <v-time-picker color="green lighten-1" header-color="primary" v-model="e4"></v-time-picker>
    </v-flex>
  </v-layout>
</template>

<script>
  export default {
    data () {
      return {
        e4: null
      }
    }
  }
</script>
