<template>
  <v-card class="overflow-hidden">
    <div class="center HeaderColor">
      <v-toolbar-title>Consult'Med</v-toolbar-title> 
     <v-btn>
      <router-link to="/"><strong>Home</strong></router-link>
    </v-btn>
    <v-btn>
 <router-link to="/About"><strong>About our doctor</strong></router-link> 
    </v-btn>
    <v-btn>
 <router-link to="/Contact"><strong>Contact</strong></router-link>
    </v-btn>


  </div>
  </v-card>
</template>



<style>
.center{
    text-align: center;
}
.HeaderColor{
   background-color:#eae9e9
}
</style>