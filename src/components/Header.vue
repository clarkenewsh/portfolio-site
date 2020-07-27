<template>
  <section id="header">
    <img src="../assets/portrait-large.jpeg" alt="Clarke portrait image">
    <h1>Hi, I'm Clarke Newsham. I am a final year Bsc Web Design and Developement Undergraduate. Passionate about solving real world problems througth the realm of UX Design and Front-End Developement</h1>
  </section>
</template>

<script>


  export default {
    name: 'Header',
  }
</script>

<style scoped>
  
  #header {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    grid-column: 2;
    /* font-family: 'Playfair Display', serif; */
    
  }

  
  
  h1 {
    color: #75928E;
    margin-top: -140px;
    font-weight: 700;
  }

  


  span {
    background: #75928E;
    line-height: 1.9;
    
  }

  span.underline {
    /* border-bottom: 2px solid #007A8A; */
    font-weight: 700;
  }

 

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
   width: 65%;
   padding-top: 100px;
   
  
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
      font-size: 180%;
    }
  }

  
</style>