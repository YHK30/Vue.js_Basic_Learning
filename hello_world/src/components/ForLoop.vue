<template>
    <h1>For Loop Tutorial</h1>
    <ul>
        <li v-for="item in technology" :key="item">
            {{ item }}
        </li>
    </ul>
    <ul>
        <li v-for="item in user" :key="item.email">
            Name is:{{ item.name }} and Email is: {{ item.email }}

        </li>
    </ul>
</template>

<script>
export default {
    name:"ForLoop",
    data(){
        
        return {
            technology:['java','react','node'],
            user:[
                {
                    name:'yash',
                    email:'yhk@gmail.com'
                },
                {
                    name:'pavan',
                    email:'pav@gmail.com'
                },
                {
                    name:'paresh',
                    email:'par@gmail.com'
                }
            ]
        }
    }
}
</script>
