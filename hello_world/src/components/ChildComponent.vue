<template>
    <h1>Child Component</h1>
    <h3>{{ name }}</h3>
    <h3>{{ user.name }} and {{ user.email }}</h3>
    <button v-on:click="getData()">Click Here</button>
</template>
<script>

export default {
    name:"ChildComponent",
   props:{
    name:String,
    user:Object,
    getData:Function
   }
}
</script>
