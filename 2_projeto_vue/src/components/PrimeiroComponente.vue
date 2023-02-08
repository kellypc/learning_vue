<template>
  <div>
    <h1>Olá Vue!</h1>
    <p>Meu nome é {{ name }} e trabalho como {{ jobTitle }}</p>
  </div>
  
</template>

<script>
  export default {
    name: 'PrimeiroComponente',
    data() {
      return {
        name: "Kelly",
        jobTitle: "Programadora"
      }
    }
  }
</script>