<template>
  <section id="MiscaMuscaMiqueyMouse">
      <input type="text" v-model="Manute" @change="ModoDiablo()">
      <h1>{{Diabloz}}</h1>
  </section>
</template>

<script>
export default {
data(){
    return{
        Manute: "",
        Diabloz:""
    }
},
methods:{
    ModoDiablo: function(){
        if(this.Manute==="negro"){
            this.Diabloz="Putos negros"
        }
    }
}
}
</script>

<style>
#MiscaMuscaMiqueyMouse input{border-style: solid;}
</style>