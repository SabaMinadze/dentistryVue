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
    <div class="hugeBox">
        <div class="box">
            <center><h2>რეზიდენტურა</h2></center>
        </div>
        <div class="bigBox">
            <center>
                <div class="cardsBox">
                    <card/>
                    <card/>
                    <card/>
                </div>
            </center>
            <br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
        </div>
    </div>
</template>

<style scoped>
/* Styles for larger screens */
@media (min-width: 1200px) {
    .box {
        height: 400px;
        width: 100%;
        background-color: rgb(180, 212, 255);
        border: 1px solid blue;
    }    

    h2 {
        font-size: 30px;
        font-weight: 700;
        color: rgb(218,165,32);
        transform: translateY(40px);
    }

    .cardsBox {
        display: flex;
        margin-top: 20px;
        align-items: center;
        text-align: center;
        gap: 30px;
        margin-left: 140px;
    }

    .text {
        color: rgb(0, 107, 238);
        font-weight: 900;
        text-align: center;
    }

    .bigBox {
        margin-top: 20px;
        text-align: center;
        transform: translateY(-300px);
    }
}

/* Styles for mobile screens */
@media (max-width: 950px) {

    .hugeBox{
        background-color: rgb(180, 212, 255);
        height: 750px;
        border: 1px solid blue;
        margin-top: 30px;
    }

    .box {
        height: auto;
        padding: 20px 10px;
        background-color: rgb(180, 212, 255);
    }    

    h2 {
        font-size: 24px;
        font-weight: 700;
        color: rgb(218,165,32);
        transform: translateY(10px);
    }

    .cardsBox {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 20px
    }

    .text {
        color: rgb(0, 107, 238);
        font-weight: 900;
        text-align: center;
        font-size: 20px;
    }

    .bigBox {
        margin-top: 10px;
        text-align: center;
        transform: none; /* Removed the Y-axis translation */
    }
}
</style>
