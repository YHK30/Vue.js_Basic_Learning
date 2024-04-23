<template>
    <h2>Get Input Values</h2>
    <input type="text" placeholder="Enter Email" v-model="email"/>
    <br/>
    <input type="text" placeholder="Enter Password" v-model="password"/>
    <br/>
    <br/>
    <button v-on:click="getDataInput()" type="button">Get Values</button>
</template>

<script>

export default {
   name:'GetInputValues',
   data(){
    return{
        email:null,
        password:null
    }
   },
   methods:{
    getDataInput(){
        console.warn("Data are: ",this.email,this.password)
    }
   }
}
</script>
