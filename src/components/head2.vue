<template>
    <div>
        <div class="box">
            <img src="../assets/logo.png" alt="error" height="110px" width="300px">
            <ul>
                <li><p>კურსები</p></li>
                <li><p>რეზიუმეები</p></li>
                <li><p>ქვიზები</p></li>
                <li><p>გამოწვევები</p></li>
                <li><p>ბლოგი</p></li>
                <li><p>კონვერტორები</p></li>
                <li><p>შესვლა</p></li>
            </ul>

        </div>
        
    </div>
</template>


<script>
</script>

<style scoped>
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
    font-size: 20px;
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
</style>