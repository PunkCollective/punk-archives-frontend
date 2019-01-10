<template>
  <div>         
    <img alt="Vue logo" src="punkarchives.png" class="logo">
    <b-jumbotron header="Starting Project">
        <p>Punk Collective Project!!</p>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  name: 'MainMessage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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

.logo {
  max-height: 100px;
}
</style>
