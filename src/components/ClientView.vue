<template>
    <div class="client-container">
        <p class="bold">Our Work</p>
        <div class="client-wrapper">
            <img class="client-img" src="../assets/pic1.jpg" alt="">
            <img class="client-img" src="../assets/pic2.jpg" alt="">
            <img class="client-img" src="../assets/pic3.webp" alt="">
            <img class="client-img" src="../assets/pic4.jpg" alt="">
            <img class="client-img" src="../assets/pic5.jpeg" alt="">
            <img class="client-img" src="../assets/pic6.jpg" alt="">
        </div>
    </div>
</template>


<style scoped>
.client-wrapper {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.client-container {
    text-align: start;
    padding-top:5% ;padding-bottom: 5%;
    background-color: var(--primary-color);
}

.bold {
    margin-left: 2%;
    font-size: 3.5em;
}

.client-img {
    height: 35dvh;
    width: 30dvw;
    margin-bottom: 3%;
}

@media screen and (max-width: 1000px) {
    .client-wrapper {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
    }

    .client-img {
        width: 100%;
    }
}

</style>