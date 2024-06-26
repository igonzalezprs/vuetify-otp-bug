<template>
  <v-container class="fill-height">
    <v-responsive class="align-centerfill-height mx-auto" max-width="900">
      <v-otp-input v-model="input" />
      <div>Current input: {{ input }}</div>
    </v-responsive>
  </v-container>
</template>

<script setup lang="ts">
  import { ref } from 'vue';

  const input = ref('');
</script>
