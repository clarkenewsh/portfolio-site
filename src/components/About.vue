<template>
  <section id="about">
    <h2>A little bit about me__</h2>
    <p>I am passionate about technology and how we can embrace it to collobrate together to do great things. I aspire to find find a organisation<strong> that share my passion for progression through tech and am activley seeking a postion as a Web Developer</strong> and <strong> UX
        Design</strong> Professional</p>
    <p>Curiosity and furtureistic thinking is what keep me ambitious to design and develop digital products
      which contribute to the progression business and society. I love to stay creative and up to date with emerging tech by getting hands dirty with 'personal passion projects' Univeristy projects. Please download my resume and check of my projects below!</p>
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
      margin-top: 40px;
    }

    /* .diagonal-box {
      min-height: 29em;
    } */
  }
</style>