<template>
  <div class="about">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <router-link :to="{ path: '/index', activeClass: 'onactive'}" >Go Index!</router-link>
  </div>
</template>

<script>
export default {
  name: 'about',
  data () {
    return {
      msg: 'About '
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
  color: #42b983;
}
</style>
