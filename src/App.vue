<script>
import AppHeader from './components/AppHeader.vue';

export default {
  data() {
    return {
      message: ''
    }
  },

  components: {
    AppHeader,
  }
}
</script>

<!-- All'interno del template ci va un solo figlio -->
<template> 
  <div>
    <AppHeader />
  </div>
</template>

<style scoped>
header {
    text-align: center;
}
</style>

