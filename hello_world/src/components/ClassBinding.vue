<template>
    <h1>CSS Binding</h1>
    <h2 :class="{green:colorfull,err:true}">Class Binding Component</h2>
    <button v-on:click="colorfull=!colorfull">Apply Style</button>
</template>
<script>

export default {
    name:'ClassBinding',
    data(){
        return{
            colorfull:false
        }
    },
    // computed:{
    //     applyStyle(){
    //         return{
    //             green:this.colorfull,
    //             err:true,
    //             other:true
    //         }
    //     }
    // }
}
</script>
<style scoped>
h1{
    color:yellowgreen
}
.green{
    background-color: bisque;
    width: 360px;
    padding: 10px;
}

.err{
    color:blueviolet
}

.other{
    font-size: 50px;
}
</style>
