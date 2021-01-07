<template>
  <img src="../assets/logo.png" alt="vue" class="block mx-auto mt-16" />
  <h1 class="text-center mt-16 text-xl">
    {{ msg }}
  </h1>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue';

export default defineComponent({
  name: 'Hello',
  setup() {
    const msg = ref('Vite + Vue 3 + TypeScript + Tailwind 2 Boilerplate');

    console.log(msg.value);

    return {
      msg,
    };
  },
});
</script>

<style lang="scss"></style>
