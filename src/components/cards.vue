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
    <div class="bigBox">
       <h1 class="text">სერვისები</h1>
       <div class="cardsBox">
            <card/>
            <card/>
            <card/>
        </div>
        <br/>
       <div class="cardsBox">
            <card/>
            <card/>
            <card/>
        </div>
        
    </div class="bigBox">
</template>
<style scoped>
@media (min-width: 1200px) and (max-width: 7777px){
    .cardsBox{
    display: flex;
    margin-top: 20px;
    align-items: center;
    text-align: center;
    gap: 30px;
    
}

.text{
    color: rgb(0,107,238);
    font-weight: 900;
    text-align: center;
}

.bigBox{
    margin-top: 20px;
    text-align: center;
}
}

@media (min-width: 220px) and (max-width: 950px){
    .cardsBox{
    display: inline-flexbox;
    text-align: center;
    gap: 90px;
    
    
}

.text{
    color: rgb(0,107,238);
    font-weight: 900;
    text-align: center;
}

.bigBox{
    margin-top: 20px;
    text-align: center;
}

}

    
</style>