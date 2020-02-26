<template>
  <v-footer padless>
    <v-col
      class="FooterColor"
      cols="12"
      
    >
      {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
    </v-col>
  </v-footer>
</template>

<style>
.FooterColor{
    background-color: #64b2cd
}
</style>