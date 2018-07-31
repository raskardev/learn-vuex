<template>
  <div class="container">
   <h1 class="mb-4">Menú del día</h1>
   <Table></Table>
  </div>
</template>

<script>
import Table from './Table';

export default {
  name: "Home",
  components: {
    Table
  },
  data() {
    return {
      
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
