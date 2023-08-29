<template>
    <div class="description-container">
        <div class="desc-wrapper">
        <p class="bold">About us</p>
        <p class="description-text">
            Snappy is a professional photography business based in Abidjan, Côte d'Ivoire. With a passion for capturing special moments, <br>
            our team of experienced photographers is dedicated to providing high-quality images that tell your unique story. Whether it's <br>
            a wedding, corporate event, or portrait session, we strive to exceed your expectations and deliver stunning photographs that <br>
            you will cherish for a lifetime. Trust Snappy to capture your memories with creativity, professionalism, and attention to detail. 
        </p>
    </div>
        
    </div>
</template>


<style scoped>

.description-container {
    background-color: var(--secondary-color);
    display: flex;
    justify-content: space-around;
    padding: 5%;
    border: 1px solid gray;
    font-size: 20px;
}

.desc-wrapper {
    display: flex;
    text-align: center;
    flex-direction: column;
}

.bold {
    font-size: 2em;
}

@media screen and (max-width: 1000px) {
    .description-container {
        display: flex;
        flex-direction: column;
    }

}

</style>