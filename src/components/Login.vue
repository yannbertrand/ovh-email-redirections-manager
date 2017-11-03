<template>
  <div id="login">
  	<router-link :to="{ name: 'home' }">Back to homepage</router-link>
  	<h1>Set app keys</h1>
    
  </div>
</template>

<script>
export default {
  name: 'login'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #35495E;
}
</style>
