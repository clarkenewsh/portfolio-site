<template>
  <section id="about">
    <h2>A little bit about me__</h2>
    <p>Hi, I am <strong>Clarke Newsham</strong>, 28 years young based in the <strong>North West</strong> of the UK. I am a final year student, studdyingat Edge Hill Univeristy a final year<strong> Bachelor Web Design and Developement</strong> Undergraduate and aspiring<strong> Web Developer</strong> and <strong> UX Design</strong> Professional.</p>
    <p>I am curious and furtureistic thinker who relishes the opportunity to design and develop digital products which have a positive impact on the progression of the human race.... this is important to me!!!. I love to stay creative and get my hands dirty with personal passion projects too. Please check them out below!</p>
  </section>
</template>

<script>
  export default {
    name: 'About',

    
  }
</script>

<style scoped>

#about {
  grid-column: 2;
}

h2 {
  font-size: 150%;
  font-weight: 900;
}

p {
padding: 20px 0px;
}

h3 {
  /* margin: 20px 0px 20px 35px; */
  
}


  @media only screen and (min-width: 768px) {
  p {
    padding: 20px 0px 20px 100px;
  }


  }



  
</style>