<template>
  <div class="first-app">
    
    <p>
      <router-link to='/second'>goto second page</router-link>
    </p>
  </div>
</template>
<script>  
  export default {
    name: "First",    
    data() {
      return {
        msg: "1234"
      }
    }
  };
</script>

<style>
</style>
