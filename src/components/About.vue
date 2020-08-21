<template>
  <section id="about">
    <div class="diagonal-box">
      <div class="content">
        <h2>A little bit about me__</h2>
          <p>Hi, I'm <strong>Clarke Newsham</strong> based in the<strong>North West, UK.</strong>
            I am a final year BSc student, studying <strong>Web Design and Development</strong> at Edge Hill Univeristy.
            Ultimately I am a aspiring<strong> Web Developer</strong> and <strong> UX
              Design</strong> Professional.</p>
          <p>I am curious and furtureistic thinker who relishes the opportunity to design and develop digital products
            which have a positive impact on the progression of the human race. This is important to me and what excites
            me about devloping great products! I love to
            stay creative by getting hands dirty with personal passion projects. Please check them out below!</p>
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
    grid-column: 1/-1;
    /* need to figure a way to take this section out of the ccs grid layout so the background can go full width */

  }


  p {
    padding: 20px 0px;
  }

  p:nth-of-type(2) {
     width: 80%;
     margin-left: auto;
   }



  .diagonal-box {
    background-image: linear-gradient(45deg, #f2f2f2, #f2f2f2);
    transform: skewY(12deg);


  }

  .content {
    max-width: 45em;
    margin: 0 auto;
    transform: skewY(-12deg);
    padding-top: 100px;
  }


  @media only screen and (min-width: 768px) {
    #about {
      margin-top: 100px;
    }


   p:nth-of-type(2) {
     width: 70%;
     margin-left: auto;
   }

    .diagonal-box {
      min-height: 29em;
    }
  }
</style>