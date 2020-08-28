<template>
  <section id="about">
    <h2>A little bit about me__</h2>
    <p>Hey, I'm Clarke Newsham, aspiring developer from the North West, UK. Im super passionte about tech and how we can embrace to develop great things that contribute to the progression of business and society.</p>
    <p>Curiosity and furtureistic thinking is what keeps me ambitious to design and develop websites using the skills and technqies I have learned ove the last 4 years. I love to stay creative and up to date with emerging tech by getting hands dirty with 'passion projects' and Univeristy projects. Please <a href="">download</a> my resume and check of my projects below!</p>
    <button class="cta-button">View my Resume</button>
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

  p {
    padding-bottom: 30px;
  }

  p:nth-of-type(2) {
    margin-left: 30px;
  }

  /* .diagonal-box {
    background-image: linear-gradient(45deg, #f2f2f2, #f2f2f2);
    transform: skewY(12deg);


  }

  .content {
    max-width: 45em;
    margin: 0 auto;
    transform: skewY(-12deg);
    padding-top: 100px;
  } */

  .cta-button {
    background: white;
    color: black;
    padding: 15px 20px;
    border: 2px solid black;
    border-radius: 50px;
    font-weight: 700;
    margin-top: 10px;
  }

  .cta-button:hover,
  .cta-button:active {
    background: black;
    color: white
  }


  @media only screen and (min-width: 768px) {
    #about {
      margin-top: 100px;
    }

    p {
    padding-bottom: 80px;
    }

    p:nth-of-type(1) {
      width: 85%;
    }

    p:nth-of-type(2) {
      width: 80%;
      margin-left: auto;

    }

    .cta-button {
      font-size: 90%;
      margin-top: 60px;
      padding: 20px 30px;
      margin-top: 20px;
    }

    /* .diagonal-box {
      min-height: 29em;
    } */
  }
</style>