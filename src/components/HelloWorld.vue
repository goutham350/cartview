<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <section>
      <b-button @click="clickMe">Login</b-button>
    </section>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
   methods: {
    clickMe() {
        this.$buefy.notification.open('Clicked!!')
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}

</style>
