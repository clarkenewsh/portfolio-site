<template>
  <section id="header">
    <img src="../assets/portrait-large.jpeg" alt="Clarke portrait image">
    <h1>Hi, I'm Clarke Newsham. I am a final year BSc Web Design and Development Undergraduate. Passionate about solving real-world problems through the realm of UX Design and Web Development</h1>
  </section>
</template>

<script>

  export default {
    name: 'Header',
  }
  
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  
  #header {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    grid-column: 2;
    
  }

  
  
  h1 {
    color: #75928E;
    margin-top: -140px;
    padding: 5px;
  }


  span {
    background: #75928E;
    line-height: 1.9;
    color: white;
    
  }
/* 
  span.underline {
    border-bottom: 5px solid #e6d7d5;;
    font-weight: 700;
    line-height: 1;
  } */

 

  img {
    max-width: 100%;
    height: auto;
    z-index: -1;
    /* box-shadow: .8rem .8rem #ccd8d9; offset-border style o*/
    
    
  }



 

  @media only screen and (min-width: 768px) {
  #header {
    display: grid;
    grid-template-columns: 1fr 1fr;
    margin: 0;

   
   
  }

  h1 {
   grid-column: 1/-1;
   grid-row: 1;
   width: 70%;
   padding-top: 100px;
   font-weight: 500;
   
  
  }



  img {
    /* place large portrait image here for desktop */
    /* width: 550px; */
    grid-column: 2;
    grid-row: 1;
    justify-self: stretch;

    
  }
}

  @media only screen and (min-width: 1400px) {
    h1 {
      font-size: 200%;
    }
  }

  
</style>