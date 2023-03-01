<template>
      <v-layout>
        <v-app-bar
          color="rgb(255, 255, 255)"
          density="compact"
        >  
          <v-app-bar-title></v-app-bar-title>
          <template v-slot:prepend>
            <v-btn icon="mdi-vuejs"></v-btn>
          </template>
          <template v-slot:append>
            <v-btn icon="mdi-minus" size="small" style="color: rgb(100, 100, 100);"></v-btn>
            <v-btn icon="mdi-close" size="small" style="color: rgb(100, 100, 100);"></v-btn>
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