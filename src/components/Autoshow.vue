<template>
  <div class="hello">
     <h1>AUTO SHOW</h1>
  </div>
</template>

<script>
export default {
  name: 'Autoshow',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
  font-family:'Samarkan Normal';
  font-size:5rem;
  color:#D6D0D0;
}
.hello {
  margin-top: 5rem;
}
@media screen and (max-width: 420px){
  .hello {
      margin-left: -0.20rem;
  }
}
</style>
