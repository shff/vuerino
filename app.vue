<template>
  <btn label="Click me" />
</template>

<script>
  const btn = requireVue("button.vue");

  export default {
    name: "app",
    components: {
      btn
    }
  };
</script>

<style>
body { background: #eee; }
</style>
