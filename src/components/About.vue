<template>
  <section id="about">
    <h2>A little bit about me</h2>
    <p>Hey, I'm Clarke Newsham, aspiring Web Developer &#38; Software Tester from the North West, UK. I'm super passionate about tech and how we can embrace it to develop great things for humanity.</p>
    <p>Curiosity and futuristic thinking are what keeps me ambitious to design and develop web apps accessible to all, using the skills and techniques I have learned over the last 4 years. I love to stay creative and up to date with emerging tech and development techniques by getting hands dirty building side projects and University studies. Please view my resume and check out my projects below!
</p>
    <a href="https://www.dropbox.com/s/7hxyre7cr5w003t/Clarke%20Newsham%20Resume%20-%20Web%20Dev%20%26%20testing.pdf?dl=0"><button class="cta-button">View my Resume</button></a>
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
    padding-bottom: 70px;
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