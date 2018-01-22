<template>
  <md-app id="app">
    <md-app-content>
      <h1>Zipper Template</h1>
      <router-view />
    </md-app-content>
  </md-app>
</template>

<script>
import Vue from 'vue'
import VueMaterial from 'vue-material'

import 'vue-material/dist/vue-material.min.css'
import 'vue-material/dist/theme/default.css'

Vue.use(VueMaterial)

export default {
  name: 'app'
}
</script>

<style>
@import "assets/material-icons.css"
</style>
