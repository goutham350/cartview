<template>
  <div class="nav">
    <h1>{{ msg }}</h1>
     
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
    msg: String
  },
   methods: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang = "less" scoped>
h3 {
  margin: 40px 0 0;
}

</style>
