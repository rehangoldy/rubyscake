<template>
  <div>
  <NavBar/>
 
  <ContentView/>
  <MyFooTer/>
 
</div>
  
  
</template>


<script>

import ContentView from './components/ContentView.vue';
import NavBar from './components/templates/NavBar.vue'
import MyFooTer from './components/templates/MyFooter.vue'



export default {
  name: 'App',
  components: {
    NavBar,
    ContentView,
    MyFooTer

}

}
</script>


