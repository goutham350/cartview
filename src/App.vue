<template>
  <div id="app">
    <b-navbar>
        <template slot="brand">
            <b-navbar-item href="/">
                <img src="./assets/logo.png">
            </b-navbar-item>
        </template>
        <template slot="start">
            <b-navbar-item href="#">
                Home
            </b-navbar-item>
            <b-navbar-item href="#">
                Documentation
            </b-navbar-item>
        </template>

        <template slot="end">
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a class="button is-primary">
                        <router-link to="/login"><strong>Sign up</strong></router-link>
                    </a>
                    <a class="button is-light">
                        <router-link to="/login">Login</router-link>
                    </a>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: rgb(26, 26, 26);
}

</style>
