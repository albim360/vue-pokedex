<template>
  <PokeDex/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import PokeDex from '@/components/PokeDex.vue';

export default defineComponent({
  name: 'App',
  components: {
    PokeDex,
  },
});
</script>

<style>

</style>
