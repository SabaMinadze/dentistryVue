<template>
    <div>
        <div class="footer">
            <center><img src="../assets/logo2.jpg" alt="error" class="footer-img"></center>
            <center><h2 class="footer-text">📞 574 42 42 38</h2></center>
            <center><hr class="footer-hr"/></center>
            <center><h2 class="footer-text">🗺️ ქ. თბილისი, დიდუბე, ვახუშტი ბაგრატიონის #19</h2></center>
        </div>
    </div>
</template>

<script>
export default {}
</script>

<style scoped>
/* Styles for larger screens */
@media (min-width: 1200px) {
    .footer {
        width: 100%;
        height: 290px;
        background-color: rgb(218,165,32);
    }

    .footer-img {
        margin-top: 30px;
        height: 150px;
        width: 300px;
        border-radius: 120px;
    }

    .footer-text {
        color: white;
        font-size: 20px;
    }

    .footer-hr {
        color: white;
        width: 700px;
    }

    
}

/* Styles for mobile screens */
@media (max-width: 950px) {
    .footer {
        width: 100%;
        padding: 20px 0;
        background-color: rgb(218,165,32);
        text-align: center;
    }

    .footer-img {
        height: 100px;
        width: 250px;
    }

    .footer-text {
        color: white;
        font-size: 16px;
        margin-top: 10px;
    }

    .footer-hr {
        color: white;
        width: 80%;
        margin: 10px auto;
    }
}
</style>
