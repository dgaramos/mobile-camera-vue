<template>
  <div id="app">
    <AppCameraView/>
  </div>
</template>

<script>
import AppCameraView from "./components/CameraView";

export default {
  name: "App",
  components: {
    AppCameraView
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
