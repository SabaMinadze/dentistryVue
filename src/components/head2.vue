<template>
    <div class="bigBox">
        <div class="box">
            <img src="../assets/logo2.jpg" alt="error" height="110px" width="190px">
            <div class="vl"></div>
            <ul>
                <li><p>მთავარი</p></li>
                <li><p>სერვისები</p></li>
                <li><p>რეზიდენტურა</p></li>
                <li><p>ჩვენი სტომატოლოგები</p></li>
                <li><p>ჩვენს შესახებ</p></li>
                <li><p>კონტაქტი</p></li>
            </ul>

        </div>
        
    </div>
</template>


<script>
</script>

<style scoped>
@media (min-width: 1200px) and (max-width: 7777px){
    .bigBox{
    position: sticky;
    top: 0;
    width: 100%;
    background-color: #333; /* Change to your desired background color */
    z-index: 1000; /* Ensure the navbar stays on top */
    box-shadow:  gray;
    border: 1px solid white;

}

.vl {
    border-left: 1px solid white;
    height: 115px;
    position: absolute;
    left: 27%;
    margin-left: -3px;
    top: 0;
}

.box{
    height: 115px;
    width: 100%;
    background-color: silver;
}

ul{
    display: flex;
    list-style: none;
    color: rgb(255,255,255);
    font-size: 18px;
    font-weight: 700;
    margin-left: 500px;
    transform: translateY(-80px);
    gap: 20px;
}

p{
    font-weight: 600;
    margin-top: 5px;
    cursor: pointer;
}

.txt{
    margin-left: 150px;
}

img{
    margin-left: 100px;
    border-radius: 20px;
    margin-top: 3px;
    border-radius: 150px;
}
}

@media (min-width: 220px) and (max-width: 950px){
    .bigBox{
    position: sticky;
    top: 0;
    width: 100%;
    background-color: #333; /* Change to your desired background color */
    z-index: 1000; /* Ensure the navbar stays on top */
    box-shadow:  rgb(132, 132, 132);
    border: 1px solid white;

}

.vl {
    border-left: 1px solid white;
    height: 80px;
    position: absolute;
    left: 27%;
    margin-left: 75px;
    top: 0;
}

.box{
    height: 80px;
    width: 100%;
    background-color: silver;
}

img{
    height: 70px;
    width: 150px;
    margin-left: 20px;
    margin-top: 5px;
    border-radius: 70px;
}

ul{
    display: flex;
    list-style: none;
    color:  rgb(180,212,255);
    font-size: 1px;
    font-weight: 700;
    margin-left: -40px;
    transform: translateY(160px);
    
}

p{
    font-weight: 600;
    margin-top: 5px;
}

.txt{
    margin-left: 1px;
}

}

</style>