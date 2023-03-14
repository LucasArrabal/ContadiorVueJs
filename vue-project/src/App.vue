<script>
export default{
  data(){
    return{
      count : 0
    }
  },
  methods:{
    increment(){
      this.count++
    }
  },
  mounted(){
    console.log(`The initial count is ${this.count}.`)
  }
}
</script>

<template>
  <main class="app">
    <h1>Indrotução a Vue.js</h1>
    <h2>Contador:</h2>
    <button @click="increment">Count is: {{ count }}</button>
  </main>
</template>




