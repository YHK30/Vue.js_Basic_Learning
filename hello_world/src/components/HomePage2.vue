<template>
    <button v-on:click="getData('Buttom 1 Clicked')">Button 1</button>
     <button v-on:click="getData('Buttom 2 Clicked')">Button 2</button> 
     <button v-on:dblclick="getData('Double clicked')">Button 3</button>
     <h1 v-on:mouseover="getConsole()">On Click event Handling</h1> 
      <input type="text" v-model="count"/><!--Two way binding-->
      <h3>{{ count }}</h3>
</template>

<script>

export default {
    name:'HomePage2',
    data(){
        return{
            count:0
        }
    },
    methods: {getData(data){
           return alert(data)
           
    },
    getConsole(){
        console.warn("function called")
    }
}
}
</script>
