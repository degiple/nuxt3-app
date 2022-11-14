<template lang="pug">
v-container
  h1 This is Nuxt3 & Vuetify3 & Volar project!
  v-btn(@click="ready = !ready") ready?
  div(class="py-3") ready: {{ ready }}
</template>

<script setup lang="ts">
const ready = ref(false);
</script>