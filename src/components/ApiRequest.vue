<template>
  <div>
    <h2>3.Запрос пользователей и их преобразование</h2>
    <button   @click="makeRequestToAPI">API REQUEST</button>
    {{ sortedRequest }}
  </div>
</template>
<script>

import axios from 'axios'

  export default {
    name: "ApiRequest",
    data() {
      return {
        name: "Vue.js",
        apiRequestResult:[],
        sortedRequest:[],
      };
    },
    methods: {
        makeRequestToAPI(){
            axios
            .get('http://jsonplaceholder.typicode.com/users')
            .then(response => { this.apiRequestResult = response.data
            console.log(this.apiRequestResult) })
            for (let i = 0; i < this.apiRequestResult.length; i++){
              this.sortedRequest.push(this.apiRequestResult[i].name + ' ' + this.apiRequestResult[i].username )
            }
             
        }
    },
  };
</script>
<style></style>
