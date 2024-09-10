<script>

export default {
  data() {
    return {
      message: 'La mia prima app con Vite!',
    }
  }
}
</script>

<!-- All'interno del template ci va un solo figlio -->
<template> 
  <div>
    <header>
        <h1> 
            {{ message }}
        </h1>
        <img src="../assets/vue.svg" alt="">
    </header>
  </div>
</template>

<style scoped>
header {
    text-align: center;
}

img{
  width: 100px;
  margin: 50px;
}
</style>

