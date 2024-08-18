<script>
import dentaCard from "../components/dentalCard.vue"
export default {
    name: 'App',
    components: {
        dentaCard,
  },
    
}
</script>

<template>
    <div>
        <div class="bigBox">
            <center><h2>ჩვენი სტომატოლოგები</h2></center>
            <div class="card">
                <dentaCard/>
            </div>
        </div>    
    </div>
</template>


<style scoped>
.bigBox{
    height: 800px;
    width: 100%;
    background-color: rgb(180,212,255);
    border: 1px solid blue;
    transform: translateY(-50px)

}

.card{
    margin-left: 70px;
    transform: translateY(20px)
}

h2{
    font-size: 30px;
    font-weight: 700;
    color: rgb(0,101,237);
    transform: translateY(20px);
}
    
</style>