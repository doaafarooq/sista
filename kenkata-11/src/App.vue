<template>
  <div id="app">
    <navbar />
    <router-view/>
    <foot/>
  </div>
</template>

<script>
import navbar from './components/navbar'
import foot from './components/foot'

export default {
  components:{
    navbar,
    foot
  }
}
</script>

<style>
  *{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
</style>
