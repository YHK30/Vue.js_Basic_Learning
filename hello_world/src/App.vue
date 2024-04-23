<template>
  <!-- How to add component to App.vue -->

  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <!-- <HomePage/> -->
  <!-- <HomePage2/> -->
  <!-- <GetInputValues/> -->
  <!-- <HomeRadioCheck/> -->
  <!-- <IfElseToggle/> -->
  <!-- <ForLoop/> -->
  <!-- <ParentComponent/> -->
  <!-- <HomeParent/> -->
<!-- <HtmlBinding/> -->
<!-- <ClassBinding/> -->
<HomePage3/>
</template>

<script>

//How to Import
import HelloWorld from './components/HelloWorld.vue'
//  import HomePage from './components/HomePage.vue'
//  import HomePage2 from './components/HomePage2.vue'
//import GetInputValues from './components/GetInputValues.vue'
//import HomeRadioCheck from './components/HomeRadioCheck.vue'
//import IfElseToggle from './components/IfElseToggle.vue';
//import ForLoop from './components/ForLoop.vue';
//import ParentComponent from './components/ParentComponent.vue'
//import HomeParent from './components/HomeParent.vue';
//import HtmlBinding from './components/HtmlBinding.vue';
//import ClassBinding from './components/ClassBinding.vue';
import HomePage3 from './components/HomePage3.vue'

export default {
  /* eslint-disable */ 
  name: 'App',
  components: {
    HelloWorld,
    // HomePage,
    // HomePage2,
    //GetInputValues
   //HomeRadioCheck
   //IfElseToggle
   //ForLoop
   //ParentComponent
   //HomeParent
    //HtmlBinding,
    //ClassBinding
    HomePage3
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
