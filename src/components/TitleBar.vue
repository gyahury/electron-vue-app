<template>
      <v-layout>
        <v-app-bar
          color="rgb(41, 34, 71)"
          density="compact"
        >  
          <v-app-bar-title></v-app-bar-title>
          <template v-slot:append>
            <v-btn icon="mdi-minus"></v-btn>
            <v-btn icon="mdi-close"></v-btn>
          </template>
        </v-app-bar>
        <v-main>
        </v-main>
      </v-layout>
  </template>

<style>
.v-toolbar__content {
    -webkit-app-region: drag;
}
</style>