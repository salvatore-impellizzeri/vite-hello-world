<script>

export default {
  data() {
    return {
      message: 'Template Vite + Vue'
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
    </header>
  </div>
</template>

<style scoped>
header {
    background-color: aquamarine;
    text-align: center;
}

h1 {
    color: lightcoral;
}
</style>

