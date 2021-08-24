<template>
  <div class="home">
    <d-container class="container" :options="{ width: 3840, height: 2160 }">
      <p>icon</p>
      <p>
        <d-icon name="check-circle" style="font-size: 100px; color: red"></d-icon>
      </p>
      <p>loading</p>
      <p>
        <d-loading :width="200" :height="200" />
      </p>
    </d-container>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { DIcon, DContainer, DLoading } from 'data-view-naive'

export default defineComponent({
  name: 'App',
  components: {
    DIcon,
    DContainer,
    DLoading
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  width: 100vw;
  height: 100vh;
}
html,
body {
  width: 100%;
  height: 100%;
}
</style>

<style lang="scss" scoped>
.home {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 100%;
  background: rgb(29, 29, 29);
  color: #fff;
  font-size: 48px;
}

.container {
  font-size: 60px;
  padding: 40px;
}
</style>
