<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Typescript Simple Login App"/>
  </div>
</template>

<script lang="ts">
// @ is an alias to /src
import Vue from "vue";
import HelloWorld from '@/components/HelloWorld.vue'

export default Vue.extend({
  name: 'Home',
  components: {
    HelloWorld
  }
});
</script>
