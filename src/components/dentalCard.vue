<script>
export default {
  name: 'dentalCard',
  props: {
    nivti: {
      required: true,
      type: Object,
    }
  }
};
</script>

<template>
  <div class="dentalCard">
    <h1>{{ nivti.name }}</h1>
    <p>{{ nivti.profession }}</p>
  </div>        
</template>

<style scoped>
.dentalCard {
  height: 330px;
  width: 270px;
  background-color: red;
}

h1 {
  color: red;
}
</style>
