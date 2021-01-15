<template>
  <div class="hello2">
    <h1>{{ text }}</h1>
   
<input type="number" v-model="nome" placeholder="edit me">
<button @click="showText">Tip</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data(){
    return{
       nome: 0,
       text: ""
    }
  },

  methods: {
    showText: function() {
      this.text = "you should tip R$: "+this.nome*0.15+" of R$: "+this.nome;
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
