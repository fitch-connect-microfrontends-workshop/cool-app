<template>
  <div id="app">
    <div class="max-w-sm mx-auto card mt-8">
      <label class="form-label mb-2">Cool App Tags</label>
      <inline-tag-input v-model="tags"></inline-tag-input>
    </div>
  </div>
</template>

<script>
import InlineTagInput from "./components/InlineTagInput";

export default {
  name: "App",
  components: {
    InlineTagInput
  },
  data() {
    return {
      tags: ["awesome", "excellent", "amazing"]
    };
  }
};
</script>

<style src="./assets/css/app.css"/>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
