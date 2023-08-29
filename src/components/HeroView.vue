<template>
    <div class="hero-container">
        <p class="hero-text bold">Capture Life's Moments </p>
        <p class="hero-text">Professional Photography capturing the essence and beauty of your <br>special moments. Book Now!</p>
    </div>
</template>

<style scoped>

.hero-container {
    background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('../assets/hero-banner.jpg');
    filter: sepia(90%);
    display: flex;
    justify-content: center;
    flex-direction: column;
    text-align: center;
    padding: 15%;
}

.hero-text {
    color: white;
    font-size: 1.5em;
}

.bold {
    font-weight: 700;
    font-size: 3.5em;
}

.hero-btn {
    background-color: #E2CFEA;
    width: fit-content;
    border: none;
    border-radius: 15px;
    padding: 1%;
    font-size: 1.25em;
}

.hero-btn-container {
    display: flex;
    justify-content: center;
}

</style>