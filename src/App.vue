<template>
    <div>
        <p v-if="msg.length > 0">
            {{msg}}
        </p>
        <p v-else>
            no text
        </p>
        <input type="text" v-model="msg">
    </div>
</template>

<script> export default {
  data () {
    return {
      msg: 'Hello World!'
    }
  }
}
</script>
<!--<template>-->
<!--<div id="app">-->
<!--<img src="./assets/logo.png">-->
<!--<router-view/>-->
<!--</div>-->
<!--</template>-->

<!--<script>-->
<!--export default {-->
<!--name: 'App'-->
<!--}-->
<!--</script>-->

<!--<style>-->
<!--#app {-->
<!--font-family: 'Avenir', Helvetica, Arial, sans-serif;-->
<!-- -webkit-font-smoothing: antialiased;-->
<!-- -moz-osx-font-smoothing: grayscale;-->
<!--text-align: center;-->
<!--color: #2c3e50;-->
<!--margin-top: 60px;-->
<!--}-->
<!--</style>-->
