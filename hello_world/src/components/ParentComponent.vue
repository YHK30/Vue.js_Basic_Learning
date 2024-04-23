<template>
    <h2>Parent Component</h2>
    <ChildComponent name="Yash Kadam" :user="user" :getData="getData"/>
</template>

<script>
import ChildComponent from './ChildComponent.vue'

export default {
    name:"ParentComponent",
    components: {
        ChildComponent
    },
    data(){
        return{
            user:{
                name:"Pavan",
                email:"pavan@gmail.com"
            }
        }
    },
    methods:{
        getData(){
            console.warn("Parent function called"),
            alert("Parent func called")
        }
    }
}
</script>
