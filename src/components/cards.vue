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
        <center><div class="cardsBox">
            <card/>
            <card/>
            <card/>
        </div></center>
        
    </div class="bigBox">
</template>
<style scoped>
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
    text-align: center
}

.bigBox{
    margin-top: 20px;
    text-align: center;
}
    
</style>