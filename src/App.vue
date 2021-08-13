<template>
  <d-icon name="check-circle" style="font-size: 30px;color: red;"></d-icon>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { DIcon } from 'data-view-naive';

export default defineComponent({
  name: 'App',
  components: {
    DIcon
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
