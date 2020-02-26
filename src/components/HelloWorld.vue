<template>
  <div class="hello">{{ message }}</div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    message: {
      type: String,
      required: true,
      default: "Hello Vue"
    }
  }
};
</script>