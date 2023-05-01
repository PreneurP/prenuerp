<template>
  <div id="app">
    <Header />
    <Services />
    <Project />
    <Prenuer />
    <Testimonial />
    <Contact />
    <Footer />
  </div>
</template>

<script>

// Import Bootstrap an BootstrapVue CSS files (order is important)
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'

import Header from './components/Header.vue'
import Services from './components/Services.vue'
import Project from './components/Project.vue'
import Prenuer from './components/Prenuer.vue'
import Testimonial from './components/Testimonial.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Header,
    Services,
    Project,
    Prenuer,
    Testimonial,
    Contact,
    Footer
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap');

#app {
  font-family: "Quicksand", Helvetica, Arial, sans-serif;
}
::-webkit-scrollbar{
  background: #D9DBE1;
  width: 8px;
}
::-webkit-scrollbar-thumb{
  background: #0B0D17;
  width: 8px;
}
</style>
