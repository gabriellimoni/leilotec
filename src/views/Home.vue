<template>
  <div class="home">
    <sales-list />
  </div>
</template>

<script>
// @ is an alias to /src
import SalesList from '@/components/SalesList.vue'

export default {
  name: 'Home',
  components: {
    SalesList,
  }
}
</script>

<style scoped>
.home {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 40vh;
}
</style>