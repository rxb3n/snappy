<template>

<NavView/>
<HeroView/>
<ClientView/>
<DescriptionView/>
<ServicesView/>
<ReviewView/>
<LocationView/>
<FooterView/>

</template>

<script>
import NavView from './components/NavView.vue'
import HeroView from './components/HeroView.vue'
import DescriptionView from './components/DescriptionView.vue'
import ServicesView from './components/ServicesView.vue'
import ReviewView from './components/ReviewView.vue'
import ClientView from './components/ClientView.vue'
import FooterView from './components/FooterView.vue'
import LocationView from './components/LocationView.vue'

export default {
  name: 'App',
  components: {
    NavView,
    HeroView,
    DescriptionView,
    ServicesView,
    ReviewView,
    ClientView,
    FooterView,
    LocationView,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap');

:root {
  --primary-color: #FFC300;
  --secondary-color: #CCCC38;
}

body, h1, h2, h3, h4, h5, h6{
  margin: 0;
  padding: 0;
  font-family: 'Playfair Display', serif;
}

</style>
