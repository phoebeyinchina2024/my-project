<template>
  <hello-world>
    {{testValue}}
  </hello-world>
</template>

<script>
export default {
  name: "test",
  data() {
    return {
      testValue: "Hello World"
    };
  }
}
</script>