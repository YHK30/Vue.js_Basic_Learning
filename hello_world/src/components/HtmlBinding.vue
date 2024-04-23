<template>
    
    <div v-html="tag1"></div>
    <div v-html="tag2"></div>
    <h1>{{ address }}</h1>
</template>
<script>

export default {
    name:'HtmlBinding',
    data(){
        return{
            tag1:"<h1>Yash Kadam</h1>",
            tag2:"<h2>yhk@gmail.com</h2>",
            address:"Malegaon,Nashik"
        }
    }
}
</script>
<style scoped>
h1,h2,div{
    color: black;
}
</style>
