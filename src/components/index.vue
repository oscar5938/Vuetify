<template>
  <section id="mr">
      <v-toolbar flat height="72">
      <v-switch
        v-model="$vuetify.theme.dark"
        inset
        label="Modo blanquista"
        persistent-hint
      ></v-switch>
    </v-toolbar>
  </section>
</template>

<script>
export default {

}
</script>

<style>
.theme--light.v-sheet{background-color: #726d6d50 !important;}
</style>