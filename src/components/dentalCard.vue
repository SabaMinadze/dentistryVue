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
        <center><div class="boX">
            <div class="dentalCard">
                <center><img src="../assets/noimage.png" alt="errors" height="200" width="280"></center>
                <center><h1>{{ nivti.name }}</h1></center>
                <center><h2>{{ nivti.profession }}</h2></center>
            </div>  
        </div></center>     
</template>

<style scoped>
@media (min-width: 1200px) and (max-width: 7777px){
  .dentalCard {
    height: 330px;
    width: 290px;
    background-color: rgb(236,244,255);
    font-size: 17px;
    margin-left: -600px;
    border-radius: 10px;
    border: 1px solid blue;
    color: rgb(0,101,237);
}

img{
    border-radius: 10px;
}

h1{
    font-size: 20px;
    font-weight: 700;
}

h2{
    font-size: 21px;
}
}


</style>
