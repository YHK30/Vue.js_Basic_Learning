<template>
    <ul>
        <li v-for="item in user" :key="item.name">      
            <UserChild :data="item"/>
        </li>
    </ul>

</template>

<script>
import UserChild from './UserChild.vue';

export default {
    /* eslint-disable */
   name:"HomeParent",
   components:{
    UserChild
   },
   data(){
        return{
            user:[{
                    name:'yash',
                    email:'yk@gmail.com'
                },
                {
                    name:'pavan',
                    email:'pj@gmail.com'
                }]
        }
    }
}
</script>
