<template>
  <v-container>
    <h1>This is Nuxt3 & Vuetify3 & Volar project!</h1>
    <v-btn @click="ready = !ready">ready?</v-btn>
    <div class="py-3">ready: {{ ready }}</div>
  </v-container>
</template>

<script setup lang="ts">
const ready = ref(false);
</script>