<template>
  <div id="app">
    <HelloWorld :message="datacontent"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  },
  data() {
    return {
      datacontent: undefined
    };
  }
};
</script>