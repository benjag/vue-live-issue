<script setup>
import { VueLive } from 'vue-live';
</script>

<template>
  <main>
    <VueLive
      code="<h1>Hello world</h1>"
      @error="(e) => console.log('Error on first example', e)"
    />
  </main>
</template>
