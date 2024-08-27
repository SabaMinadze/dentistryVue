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
       <div class="cardsBox">
            <card/>
            <card/>
            <card/>
        </div>
        <br/>
       <div class="cardsBox">
            <card/>
            <card/>
            <card/>
        </div>
        <br/><br/><br/>
    </div>
</template>

<style scoped>
/* Styles for larger screens */
@media (min-width: 1200px) {
    .cardsBox {
        display: flex;
        margin-top: -15px;
        align-items: center;
        justify-content: center;
        gap: 30px;
        margin-top: 10px;
    }

    .text {
        color: silver;
        font-weight: 900;
        text-align: center;
    }

    .bigBox {
        margin-top: 20px;
        text-align: center;
    }
}

/* Styles for tablet screens */
@media (min-width: 600px) and (max-width: 1199px) {
    .cardsBox {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
        margin-top: 10px;
    }

    .text {
        color: rgb(0, 0, 0);
        font-weight: 900;
        text-align: center;
        font-size: 28px;
    }

    .bigBox {
        margin-top: 15px;
        padding: 0 20px;
    }
}

/* Styles for mobile screens */
@media (max-width: 599px) {
    .cardsBox {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 15px;
        margin-top: 10px;
    }

    .text {
        color: rgb(0, 0, 0);
        font-weight: 900;
        text-align: center;
        font-size: 24px;
    }

    .bigBox {
        margin-top: 10px;
        padding: 0 10px;
        background-color: rgb(180,212,255);
        margin-top: 30px;
    }
}
</style>

