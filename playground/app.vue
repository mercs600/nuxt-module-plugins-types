<template>
  <div>
    Nuxt module playground!
  </div>
</template>

<script setup lang="ts">
import { useNuxtApp } from '#app';

const nuxtApp = useNuxtApp()
nuxtApp.$myPlugin.hello
</script>
