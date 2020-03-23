<template>
  <button>
    {{ label }}
  </button>
</template>

<script>
  export default {
    name: "btn",
    props: {
      label: String
    }
  };
</script>

<style>
body { background: #eee; }
</style>
