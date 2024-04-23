<template>
    
    <label for="java">Java</label>
    <input type="checkbox" value="Java" v-model="technology" id="java">
    <br/>
    <label for="node">Node</label>
    <input type="checkbox" value="Node" v-model="technology" id="node">
    <br/>
    <label for="react">React</label>
    <input type="checkbox" value="React" v-model="technology" id="react">
    <br/>
    <h3>Selected Technology: {{ technology }}</h3>

    <label for="developer">Developer</label>
    <input type="radio" value="Developer" v-model="role" id="developer">
    <br/>

    <label for="tester">Tester</label>
    <input type="radio" value="Tester" v-model="role" id="tester">
    <br/>

    <h3>Role: {{ role }}</h3>
</template>

<script>


export default {
  data(){
    return{
    name:"HomeRadioCheck",
    technology:[],
    role:null,
  }
}
}
</script>
