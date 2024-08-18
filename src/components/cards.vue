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
        <h1 class="text">სერვისები</h1>
        <center><div class="cardsBox">
            <card/>
            <card/>
            <card/>
        </div></center>
        
    </div>
</template>
<style scoped>
.cardsBox{
    display: flex;
    margin-top: 100px;
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
    
</style>