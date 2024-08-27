<template>
    <div>
        <center><div class="bigBox">
            <center><h2>ჩვენი მიღწევები</h2></center>
            <img src="../assets/kbili1.jpg" alt="error" height="300" width="300">
            <img src="../assets/kbili2.jpg" alt="error" height="300" width="300">
            <img src="../assets/kbili3.jpg" alt="error" height="300" width="300">
            <img src="../assets/kbili4.jpg" alt="error" height="300" width="300">
        </div></center>
        
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
@media (min-width: 1200px) and (max-width: 7777px){
    .bigBox{
        transform: translateY(-440px);
        height: 10px;
}

img{
    border: 5px solid silver;
    margin-left: 30px;
    border-radius: 10px;
    width: 270px;

}

h2{
    font-size: 30px;
    font-weight: 700;
    color: silver;
    transform: translateY(-30px);
}

}

@media (min-width: 220px) and (max-width: 950px){
    .bigBox{
        margin-top: 40px;
        background-color: rgb(180,212,255);
    
}

img{
    border: 5px solid silver;;
    margin-left: 30px;
    border-radius: 10px;
    width: 270px;

}

h2{
    font-size: 28px;
    font-weight: 700;
    color: silver;
    transform: translateY(-3px);
}


}


</style>