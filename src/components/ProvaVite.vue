<script>
export default {
  name: "ProvaVite",
  data(){
    return{
      appTitle: "La mia prima app con Vite"
    }
  }
}
</script>
<template>
  <h2>{{appTitle}}</h2>
</template>


<style scoped>
  h2{
    font-size: 3rem;
    color: blue;
  }
</style>