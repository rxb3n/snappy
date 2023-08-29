<template>
    <div class="serv-container">
        <p class="big bold" id="services">Our Services</p>

        <div class="serv-wrapper">

            <div class="serv-card">
                <img class="serv-img" src="../assets/serv1.jpg" alt="">
                <p class="bold">Studio Photography</p>
                <p>We offer high-quality photography services for your <br>products and events, with a team of experienced <br>photographers.</p>
            </div>

            
            <div class="serv-card">
                <img class="serv-img" src="../assets/serv2.jpg" alt="">
                <p class="bold">Outdoor Photography</p>
                <p>Our team captures stunning moments in the outdoors, be it <br>your wedding day or a scenic location shoot.</p>
            </div>

            
            <div class="serv-card">
                <img class="serv-img" src="../assets/serv3.webp" alt="">
                <p class="bold">Photo Editing</p>
                <p>Our professional photo editors are skilled in retouching and <br>enhancing images to give you perfect results every time.</p>
            </div>

        </div>

    </div>

</template>


<style scoped>

#services {
    text-align: center;
}
.serv-container {
    padding: 5%;
    background-color:var(--secondary-color);
}

.serv-wrapper {
    background-color:var(--secondary-color);
    display: flex;
    justify-content: space-around;
}

.serv-img {
    border-radius: 18px;
    height: 40dvh;
    width: 25dvw;
}

.bold {
    font-size: 1.5em;
}

.big {
    font-size: 2.5em;
}


@media screen and (max-width: 1000px) {
    .serv-wrapper {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
    }

    .serv-img {
        width: 90%;
    }
}

</style>