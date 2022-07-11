<template>
  <v-app>
    <Preloader/>
    <v-main class="main-container">
      <Header/>
      <About/>
      <Technologies/>
      <Projects/>
      <Contact/>
      <Footer/>
    </v-main>
  </v-app>
</template>

<script>
import Header from './components/Header';
import About from './components/about';
import Preloader from './components/preloader';
import Technologies from './components/technologies';
import Projects from './components/projects';
import Contact from './components/contact';
import Footer from './components/footer';


export default {
  name: 'App',

  components: {
    Header,
    Footer,
    Contact,
    About,
    Preloader,
    Technologies,
    Projects,
  },

  data: () => ({
    //
  }),
};
</script>
<style scoped>
.main-container{
  overflow-x: hidden;
  
}
</style>
