<template>
  <v-app-bar
    app
    clipped-left
    color="amber"
  >
    <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
    <span class="title ml-3 mr-5">Google&nbsp;<span class="font-weight-light">Keep</span></span>
    <v-text-field
      solo-inverted
      flat
      hide-details
      label="Search"
      prepend-inner-icon="search"
    ></v-text-field>
    <v-spacer></v-spacer>
  </v-app-bar>
</template>

<script>
export default {

}
</script>

<style>

</style>