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
  background-image: radial-gradient(#75928e 1px, transparent 0);
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
  color: black;
  margin: 0px 3%;
  line-height: 1.6;
  
  
}

h1,h2 {
  color: black;
  padding: 15px 0px;
  font-family: 'Playfair Display', serif;
    
}

h3, h4 {
  font-family: 'Playfair Display', serif;
}

 section, header {
  margin-bottom: 60px;
}


  @media only screen and (min-width: 768px) {
 #app {
    display: grid;
    grid-template-columns: 3% 1fr 3%;
    grid-gap: 20px;
    font-size: 20px;
    margin: 0;
  }

   section, header {
    margin-bottom: 100px;
  }


  h2 {
    font-size: 180%;
    font-weight: 900;
  }


}

 @media only screen and (min-width: 1024px) {
    
  h2 {
    font-size: 200%;
  }

  #app {
    font-size: 22px;
  }



 }

  @media only screen and (min-width: 1400px) {
 #app {
    display: grid;
    grid-template-columns: 15% 1fr 15%;
    grid-gap: 30px;
    margin: 0;
  }

   section, header {
    margin-bottom: 100px;
}

}






</style>
