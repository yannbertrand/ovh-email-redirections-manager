<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li><router-link :to="{ name: 'login' }">Set OVH app keys</router-link></li>
      <li><router-link :to="{ name: 'domains' }">Choose domain</router-link></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello'
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
