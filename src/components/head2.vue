<template>
    <div class="bigBox">
        <div class="box">
            <img src="../assets/logo.png" alt="error" height="110px" width="300px">
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
    box-shadow:  rgb(0,101,237);
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
    background-color: rgb(0,101,237);
    color: rgb(108,34,166);
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
}
}

@media (min-width: 220px) and (max-width: 950px){
    .bigBox{
    position: sticky;
    top: 0;
    width: 100%;
    background-color: #333; /* Change to your desired background color */
    z-index: 1000; /* Ensure the navbar stays on top */
    box-shadow:  rgb(0,101,237);
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
    background-color: rgb(0,101,237);
    color: rgb(108,34,166);
}

img{
    margin-left: 1px;
    height: 60px;
    width: 160px;
    margin-left: 20px;
    margin-top: 10px;
}

ul{
    display: flex;
    list-style: none;
    color: rgb(0, 0, 0);
    font-size: 7px;
    font-weight: 700;
    margin-left: 5px;
    transform: translateY(-80px);
    gap: 20px;
}

p{
    font-weight: 600;
    margin-top: 5px;
    cursor: pointer;
}

.txt{
    margin-left: 1px;
}


}

</style>