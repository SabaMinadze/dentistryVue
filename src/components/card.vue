<template>
    <div>
        <div class="box">
            <h2>პარადონტოლოგია</h2>
        </div>
    </div>
</template>

<script>
export default {}
</script>

<style scoped>
/* Styles for larger screens */
@media (min-width: 1200px) {
    .box {
        height: 240px;
        width: 400px;
        border-radius: 10px;
        background-color: rgb(0, 101, 237);
    }

    h2 {
        font-weight: 600;
        color: white;
        transform: translateY(90px);
    }
}

/* Styles for mobile screens */
@media (max-width: 950px) {
    .box {
        height: 180px;
        width: 370px;
        border-radius: 10px;
        background-color: rgb(0, 101, 237);
    }

    h2 {
        font-weight: 600;
        color: white;
        font-size: 20px; /* Adjusted font size for mobile */
        transform: translateY(70px); /* Adjusted Y-axis translation */
        text-align: center; /* Center the text */
    }
}
</style>


