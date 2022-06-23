<template>
  <NavBar :AppName="this.appName"></NavBar>
  <router-view/>
</template>


<style>

</style>
<script>
import NavBar from "@/components/NavBar";

export default {
  name: 'App',
  data () {
      return {
    appName: 'Vue Shop'
    }
  },
  components: {NavBar}
}
</script>