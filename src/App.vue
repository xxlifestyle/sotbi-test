<template>

  <logo></logo>
</template>

<script>
import Logo from './components/Logo.vue';


export default {
  name: "App",
  components: {
    Logo
    
  },
};
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body{
  display: flex;
  justify-content: center;
}
</style>
