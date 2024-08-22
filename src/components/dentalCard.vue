<script>
export default {
  name: 'dentalCard',
  props: {
    nivti: {
      required: true,
      type: Object,
    }
  }
};
</script>

<template>
        <center><div class="boX">
            <div class="dentalCard">
                <center><img src="../assets/noimage.png" alt="errors" height="200" width="280"></center>
                <center><h1>{{ nivti.name }}</h1></center>
                <center><h2>{{ nivti.profession }}</h2></center>
            </div>  
        </div></center>     
</template>

<style scoped>
@media (min-width: 1200px) and (max-width: 7777px){
  .dentalCard {
    height: 330px;
    width: 290px;
    background-color: rgb(236,244,255);
    font-size: 17px;
    margin-left: -600px;
    border-radius: 10px;
    border: 1px solid blue;
    color: rgb(0,101,237);
}

img{
    border-radius: 10px;
}

h1{
    font-size: 20px;
    font-weight: 700;
}

h2{
    font-size: 21px;
}
}

/* Styles for laptops and tablets */
@media (min-width: 950px) and (max-width: 1199px) {
    .dentalCard {
        height: 300px;
        width: 80%;
        max-width: 350px;
        background-color: rgb(236, 244, 255);
        font-size: 16px;
        margin: 20px auto; /* Center card with margin */
        border-radius: 10px;
        border: 1px solid blue;
        color: rgb(0, 101, 237);
        text-align: center;
    }

    .card-img {
        height: 180px;
        width: auto;
        border-radius: 10px;
    }

    h1 {
        font-size: 18px;
        font-weight: 700;
    }

    h2 {
        font-size: 19px;
    }
}

/* Styles for mobile screens */
@media (max-width: 949px) {
    .dentalCard {
        height: auto;
        width: 90%;
        max-width: 300px;
        background-color: rgb(236, 244, 255);
        font-size: 15px;
        margin: 10px auto; /* Center card with margin */
        border-radius: 10px;
        border: 1px solid blue;
        color: rgb(0, 101, 237);
        text-align: center;
    }

    .card-img {
        height: 150px;
        width: auto;
        border-radius: 10px;
    }

    h1 {
        font-size: 16px;
        font-weight: 700;
    }

    h2 {
        font-size: 16px;
    }
}

/* Styles for very small screens */
@media (max-width: 600px) {
    .dentalCard {
        width: 95%;
        font-size: 14px;
        margin: 5px auto; /* Smaller margin for very small screens */
    }

    .card-img {
        height: 120px;
        width: auto;
    }

    h1 {
        font-size: 14px;
    }

    h2 {
        font-size: 14px;
    }
}
</style>
