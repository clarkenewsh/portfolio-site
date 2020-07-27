<template>
  <div id="app">
    <Nav/>
    <Header/>
    <About/>
    <Hobbies/>
    <Projects/>
    <Footer/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Nav from './components/Nav';
import Header from './components/Header';
import About from './components/About';
import Hobbies from './components/Hobbies';
// import Skills from './components/Skills';
import Projects from './components/Projects';
import Footer from './components/Footer';

export default {
  name: 'App',
  components: {
    Nav,
    Header,
    About,
    Hobbies,
    Projects,
    Footer,
  }
}
</script>

<style>

.dotted-grid {
  background: white;
  background-image: radial-gradient(black 1px, transparent 0);
  background-size: 40px 40px;
  background-position: -19px -19px;
}

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}



#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin: 0px 3%;
  line-height: 1.6;
  
  
}



  @media only screen and (min-width: 768px) {
 #app {
    display: grid;
    grid-template-columns: 3% 1fr 3%;
    grid-gap: 20px;
    font-size: 22px;
    margin: 0;
  }

}

  @media only screen and (min-width: 1400px) {
 #app {
    display: grid;
    grid-template-columns: 10% 1fr 10%;
    grid-gap: 100px;
    margin: 0;
  }

}



h1,h2,h3,h4 {
    /* font-family: 'Playfair Display', serif; */
    
    color: black;
    padding: 15px 0px;
    
}


</style>
