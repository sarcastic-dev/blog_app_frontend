<template>
  <div id="app">
    <NavBar></NavBar>
    <router-view></router-view>
 
  </div>

</template>

<script>

import NavBar from './components/navbar'

export default {
  name: 'App',
  components: {
    NavBar ,
    
  }
}
</script>
