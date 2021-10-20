<template>
<div>
  <logo/>
  <hover/>
  <api-request/>
  </div>
</template>

<script>
import ApiRequest from './components/ApiRequest.vue';
import Hover from './components/Hover.vue';
import Logo from './components/Logo.vue';


export default {
  name: "App",
  components: {
    Logo,
    Hover,
    ApiRequest
    
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
