<template>
  <div class="sale">
    <h1>Leilão Tal</h1>
    <h4>Descrição do leilão e tal...</h4>

    <h4>Último lance: {{ last_offer  }}</h4>

    <div class="offer-handler">
      <h4>Novo lance</h4>
      <input type="text" v-model="new_offer_value">

      <h4>Cliente</h4>
      <select>
        <option value="1">Gabriel Limoni</option>
        <option value="2">Gentil Filho</option>
        <option value="3">Bruno Limoni</option>
      </select>
      
      <br>
      <br>

      <button>Salvar Lance</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Sale',
  components: {
  },

  data () {
    return {
      last_offer: 'R$ 1.200,00',
      new_offer_value: 1250,
    }
  },
}
</script>

<style scoped>
/* .sale { */
  /* display: flex;
  justify-content: center;
  align-items: center; */
/* } */
</style>