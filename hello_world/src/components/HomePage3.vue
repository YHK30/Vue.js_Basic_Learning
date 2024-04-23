<template>
    <h1>HomePage3 Details</h1>
    <Student :name="name"/>
</template>
<script>
import Student from './Student.vue';

export default {
    name:'HomePage3',
    components:{
        Student
    },
    data(){
        return{
            name:"Yash Kadam"
        }
    }
}
</script>
