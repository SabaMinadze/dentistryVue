<script>
import dentalCard from "../components/dentalCard.vue";
import data from '../data.json';

export default {
  name: 'App',
  components: {
    dentalCard,
  },
  data() {
    return {
      dental1: data,
    }
  }
};
</script>


<template>
    <div>
      <div class="bigBox">
        <center><h2>ჩვენი სტომატოლოგები</h2></center>
        <div class="card">
          <dentalCard v-for="(item, index) in dental1" :key="item.id" :nivti="item"/>
        </div>
      </div>
    </div>
  </template>


<style scoped>
.bigBox{
    background-color: blue;
}
</style>
