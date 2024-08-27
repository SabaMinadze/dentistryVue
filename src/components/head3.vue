<template>
    <div>
        <div class="box">
            <center><h1>ალგანი დენტი</h1></center>
            <center><button>კითხვა გაქვთ? დაგვიკავშირდით</button></center>
            <center><img src="../assets/logo2.png" alt="error"></center>
        </div>
        
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
@media (min-width: 1200px) and (max-width: 7777px){
    .box{
    width: 100%;
    height: 450px;
    background-color: rgb(180,212,255);
}

h1{
    
    color: rgb(0,101,237);
    font-weight: 900;
    margin-left: -930px;
    transform: translateY(170px);
    font-size: 28px;
}

button{
    margin-left: -830px;
    background-color: rgb(218,165,32);
    width: 350px;
    height: 40px;
    border-radius: 15px;
    font-size: 20px;
    color: white;
    font-weight: 600;
    border: 1px solid white;
    transform: translateY(180px);
    cursor: pointer;
}

button:hover{
    margin-left: -830px;
    background-color: rgb(147, 114, 31);
    width: 350px;
    height: 40px;
    border-radius: 15px;
    font-size: 20px;
    color: white;
    font-weight: 600;
    border: 1px solid white;
    transform: translateY(180px);
    cursor: pointer;

}

img{
    margin-left: 570px;
    transform: translateY(30px);
}
}

@media (min-width: 220px) and (max-width: 950px){
    .box{
    width: 100%;
    height: 400px;
    background-color: rgb(180,212,255);
}

h1{
    color: rgb(0,101,237);
    font-weight: 900;
    transform: translateY(270px);
    font-size: 25px;
}

button{
    background-color: rgb(0,101,237);
    width: 350px;
    height: 40px;
    border-radius: 15px;
    font-size: 20px;
    color: white;
    font-weight: 600;
    border: 1px solid white;
    transform: translateY(290px);
    cursor: pointer;
}

button:hover{
    margin-left: 180px;
    background-color: rgb(9, 84, 182);
    width: 350px;
    height: 40px;
    border-radius: 15px;
    font-size: 20px;
    color: white;
    font-weight: 600;
    border: 1px solid white;
    transform: translateY(290px);
    cursor: pointer;
    transition: 0.5s;

}

img{
    height: 170px;
    width: 170px;
    transform: translateY(-70px);
}

}

    
</style>