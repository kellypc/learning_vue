<template>
  <h1>Meu nome é: {{ name }}</h1>
</template>

<script>
  export default {
    name: 'LifeCycle',
    data() {
      return {
        name: 'Ainda não sei'
      }
    },
    created(){
      setTimeout(() => {
        this.name = "Kelly"
      }, 1000)
    },
    mounted() {
      setTimeout(() => {
        this.name = "Desconhecido"
      }, 2000)
    }
  }
</script>