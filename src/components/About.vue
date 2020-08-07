<template>
  <section id="about">
    <div class="diagonal-box">
      <div class="content">
        <h2>A little bit about me__</h2>
        <p>Hi, I am <strong>Clarke Newsham</strong>, 28 years young based in the <strong>North West</strong> of the UK.
          I am a final year student, studdyingat Edge Hill Univeristy a final year<strong> Bachelor Web Design and
            Developement</strong> Undergraduate and aspiring<strong> Web Developer</strong> and <strong> UX
            Design</strong> Professional.</p>
        <p>I am curious and furtureistic thinker who relishes the opportunity to design and develop digital products
          which have a positive impact on the progression of the human race.... this is important to me!!!. I love to
          stay creative and get my hands dirty with personal passion projects too. Please check them out below!</p>
      </div>
    </div>

  </section>
</template>

<script>
  export default {
    name: 'About',


  }
</script>

<style scoped>
  #about {
    grid-column: 2; /* need to figure a way to take this section out of the ccs grid layout so the background can go full width */
    
  }


  p {
    padding: 20px 0px;
  }


  .diagonal-box {
    background-image: linear-gradient(45deg, #f2f2f2, #f2f2f2);
    transform: skewY(-7deg);
    
    
  }

  .content {
    /* max-width: 50em; */
    margin: 0 auto;
    transform: skewY(7deg);
  }


  @media only screen and (min-width: 768px) {
    #about {
      margin-top: 100px;
    }
    
    p {
      padding: 20px 0px 20px 70px;
    }

    .diagonal-box {
      min-height: 22em;
    }
  }
</style>