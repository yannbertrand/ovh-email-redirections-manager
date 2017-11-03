<template>
  <div id="domains">
    <router-link :to="{ name: 'home' }">Back to homepage</router-link>
    <h1>Domains</h1>
    <ul>
      <li></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'domains'
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
