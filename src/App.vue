<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import MainMenu from './components/shared/MainMenu.vue'
</script>

<template>
  <v-layout class="rounded rounded-md">
    <v-app-bar>
      <MainMenu></MainMenu>
    </v-app-bar>

    <v-navigation-drawer>
      <v-list>
        <v-list-item>
          <v-btn block prepend-icon="mdi-plus" variant="tonal">Block Button</v-btn>
        </v-list-item>
        <v-list-item>
          <v-btn block prepend-icon="mdi-plus" variant="tonal">Block Button</v-btn>
        </v-list-item>
        <v-list-item>
          <v-btn block prepend-icon="mdi-plus" variant="tonal">Block Button</v-btn>
        </v-list-item>
        <v-list-item>
          <v-btn block prepend-icon="mdi-plus" variant="tonal">Block Button</v-btn>
        </v-list-item>
        <v-list-item>
          <v-btn block prepend-icon="mdi-plus" variant="tonal">Block Button</v-btn>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>

    <v-main class="d-flex align-center justify-center" style="min-height: 300px;">
      <RouterView />
    </v-main>
  </v-layout>
</template>

<style scoped>

</style>
