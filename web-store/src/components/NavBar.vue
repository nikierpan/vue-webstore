<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-transparent">
    <div class="container-fluid">
      <router-link to="/" class="navbar-brand">
        {{ AppName }}
      </router-link>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
  props: [
    'AppName'
  ]
}
</script>

<style scoped>

</style>