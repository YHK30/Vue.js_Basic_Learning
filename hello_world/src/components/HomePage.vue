<template>
    <div>
    <h1>Home Component {{ 10+15 }}</h1><!--</h1>Interpolation-->
    <h1>Email {{ email }}</h1>
    <h1>Mobile No {{ mobNo }}</h1>
    <h1>Mobile No {{ mobNo== 987654321 }}</h1>
    <h1>Name {{ getName('YHK') }}</h1>
    <h2>{{ getData() }}</h2>
</div>
</template>
<script>
// How to export
export default {
   name:'HomePage',
//    data(){
//     return{
//         email:'yash@123.com',
//         mobNo:1234567890,
//         getName:function(){
//             return'Yash Kadam'
//         }
//     }
//    }
    data(){
        return{
            email:'yashk@mkcl.com'
        }
    },
    methods:{
        getName(name){
            return name;
        },
        getData(){
            return{
                name:'yash',
                // email:'yash@90.com'
                email:this.email
            }
        }
    }
}
</script>

<style scoped>
h1{
    color: orange;
}
</style>
