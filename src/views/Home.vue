<template>
  <div class="home">
    <img alt="Logo" src="../assets/logo.png" style="max-width: 10%">
    <HelloWorld msg="Geofence Take Home Assignment"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
};
</script>
