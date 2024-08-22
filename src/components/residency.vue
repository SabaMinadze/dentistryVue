<script>
import card from '../components/card.vue'
export default {
    name: 'App',
    components: {
    card,
  },
    
}
</script>

<template>
    <div>
        <div class="box">
            <center><h2>რეზიდენტურა</h2></center>
            </div>
            <div class="bigBox">
            <center><div class="cardsBox">
            <card/>
            <card/>
            <card/>
            </div></center>
            <br/>
    </div class="bigBox">        
    </div>
</template>
<style scoped>

@media (min-width: 1200px) and (max-width: 7777px){
    box{
    height: 400px;
    width: 100%;
    background-color: rgb(180,212,255);
    border: 1px solid blue;
}    

h2{
    font-size: 30px;
    font-weight: 700;
    color: rgb(0,101,237);
    transform: translateY(40px);
}


.cardsBox{
    display: flex;
    margin-top: 20px;
    align-items: center;
    text-align: center;
    gap: 30px;
    margin-left: 150px;
}

.text{
    color: rgb(0,107,238);
    font-weight: 900;
    text-align: center;
}

.bigBox{
    margin-top: 20px;
    text-align: center;
    transform: translateY(-300px);
}

}

.box{
    height: 400px;
    width: 100%;
    background-color: rgb(180,212,255);
    border: 1px solid blue;
}

@media (min-width: 220px) and (max-width: 950px){}


</style>