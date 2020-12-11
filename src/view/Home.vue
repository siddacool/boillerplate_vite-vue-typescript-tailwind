<template>
  <Hello />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Hello from '../components/Hello.vue';

export default defineComponent({
  name: 'HomeView',
  components: {
    Hello,
  },
});
</script>

<style lang="scss">
.home {
  min-height: inherit;
}
</style>
