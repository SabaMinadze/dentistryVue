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
        <center><h2 class="txt">ჩვენი სტომატოლოგები</h2></center>
        <div class="card">
          <dentalCard v-for="(item, index) in dental1" :key="item.id" :nivti="item" class="cards"/>
        </div>
        <br/><br/>
      </div>
    </div>
    <br/>
  </template>


<style scoped>
@media (min-width: 1200px) and (max-width: 7777px){
  .bigBox{
    background-color: white;
    border: 1px solid gray;
  }  

.card{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin-left: 550px;
}

.cards{
    flex: 0 0 calc(33.33% - 10px); /* 33.33% width minus spacing */
    margin-top: 20px;
}

.txt{
    font-size: 30px;
    font-weight: 700;
    color: silver;
}
}

@media (min-width: 220px) and (max-width: 950px){
  .bigBox{
    background-color: white;
    border: 1px solid gray;
    margin-top: 50px;
}

  .txt{
      color: silver;
      font-weight: 900;
      text-align: center;
      font-size: 24px;
  }

}

</style>
