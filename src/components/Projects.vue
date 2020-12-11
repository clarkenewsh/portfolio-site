<template>
  <section id="projects">
    <h2>My Projects</h2>
    <div class="cards">
      <figure class="feature-card">
        <div>
          <h3 class="project-title">PopUps Website</h3>
          <h4 class="project-sub-title">Passion Project</h4>
          <p>PopUps landing page was created on the back of the growing popularity of pop-up reatilers and cusine.
            Developed using HTML5, CCS3, Flexbox and Netlify</p>
        </div>
        <img src="../assets/popups-thumb.png" alt="">
        <div class="project-cta">
          <a href="https://github.com/clarkenewsh/PopUps-Landing-Page">View on GitHub <i class="fab fa-github"></i></a>
        </div>
      </figure>
      <figure class="feature-card">
        <div>
          <h3 class="project-title">DC Decorating Contractors Website</h3>
          <h4 class="project-sub-title">Passion Project</h4>
          <p>DC Decorating Contractors is static website to advertise a local business services. Developed using
            Bootstrap, Javascript and Netlify</p>
        </div>
        <img src="../assets/dc-decor-thumb.png" alt="">
        <div class="project-cta">
          <a href="https://github.com/clarkenewsh/DC-Decorating-Services-Site">View on GitHub <i
              class="fab fa-github"></i></a>
        </div>
      </figure>
      <figure class="feature-card">
        <div>
          <h3 class="project-title">Fashion Brand Landing Page</h3>
          <h4 class="project-sub-title">Passion Project</h4>
          <p>PopUps Landing page was created on the back of the growing popularity of pop-up reatilers and cusine. The
            landing page was designed and coded using HTML5 and CC3.</p>
        </div>
        <img src="../assets/landing-fashion-thumb.png" alt="">
        <div class="project-cta">
          <a href="https://github.com/clarkenewsh/LandingPage-FashionMarketing">View on GitHub <i
              class="fab fa-github"></i></a>
        </div>
      </figure>
      <figure class="feature-card">
        <div>
          <h3 class="project-title">PaymentShield Portal App</h3>
          <h4 class="project-sub-title">University Project</h4>
          <p>A real-life client project to develop a customer portal for a Insurance broker. Developed using React,
            Contentful and Heroku.</p>
        </div>
        <img src="" alt="">
        <div class="project-cta">
          <a href="https://bitbucket.org/team2employability/paymentshield/src/master/">View on Bitbucket<i
              class="fab fa-github"></i></a>
        </div>
      </figure>
      <figure class="feature-card">
        <div>
          <h3 class="project-title">Academic Course Tracker Web App</h3>
          <h4 class="project-sub-title">University Project</h4>
          <p>Second year university project to model and develop a Academic Course Tracker aimed at academics to manage
            and show course data and related learning. Developed using vanllia JavaScript and deployed with Netlify.</p>
        </div>
        <img src="../assets/academic-track-thumb.png" alt="">
        <div class="project-cta">
          <a href="https://github.com/clarkenewsh/Academic-Tack-WebApp">View on GitHub <i class="fab fa-github"></i></a>
        </div>
      </figure>
      <figure class="feature-card">
        <div>
          <h3 class="project-title">SpaceX API Client</h3>
          <h4 class="project-sub-title">Passion Project (Live prototype)</h4>
          <p>Space X Api client GUI showing recent launches, rocket data and more cool stuff!</p>
        </div>
        <img src="../assets/spacex.jpg" alt="">
        <div class="project-cta">
          <a href="https://github.com/clarkenewsh/SpaceX-WebApp">View on GitHub <i class="fab fa-github"></i></a>
        </div>
      </figure>
      <figure class="feature-card">
        <div>
          <h3 class="project-title">UniTap</h3>
          <h4 class="project-sub-title">Passion Project (Live prototype)</h4>
          <p>A water re-fill locator for my university campus in an effort to reduce the use of single-use plastics.
            Developed using HTML5, CSS, JavaScript, Apache Cordova & hosted with Netlify</p>
        </div>
        <img src="" alt="">
        <div class="project-cta">
          <a href="https://github.com/clarkenewsh/Uni-Tap">View on GitHub <i class="fab fa-github"></i></a>
        </div>
      </figure>
      <figure class="feature-card">
        <div>
          <h3 class="project-title">Survey CMS Platform </h3>
          <h4 class="project-sub-title">University Project</h4>
          <p>A CRUD CMS platform aimed at reserachers to create surveys, collect resulting data and to analyse
            responses. Developed with PHP/Laravel and MySql</p>
        </div>
        <img src="" alt="">
        <div class="project-cta">
          <a href="https://bitbucket.org/23686014/questionaireadminapp/src/master/">View on GitHub <i
              class="fab fa-github"></i></a>
        </div>
      </figure>
      <!-- testing vuejs template syntax here, computed values, key binding, data etc -->
      <!-- <figure
        v-for="project in projects"
        v-bind:key="project.id"
        v-bind:title="project.title"
        class="feature-card">
          <h3>{{ project.title }}</h3>
          <p>{{ project.detail }}</p>
          <a href="">'View on GitHub<i class="fab fa-github"></i></a>
      </figure>
       -->


    </div>

  </section>
</template>

<script>
  export default {
    name: 'Projects',

  }

  // data: function() {
  //   return {
  //         projects: [
  //         { id: 1, title: 'UniTap', detail: 'A water refill point locator for University campus in a affect to reduce single use plastics', link:'https://github.com/clarkenewsh/Uni-Tap' },
  //         { id: 2, title: 'UniTap App' },
  //         { id: 3, title: 'Why Vue is so fun' }
  //       ]
  //   };
  // }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #projects {
    grid-column: 2;
    text-align: center;
  }

  h2 {
    margin-bottom: 50px;
  }

  .cards {
    display: grid;
    grid-template-columns: 1fr;
    grid-row-gap: 70px;
    text-align: center;
  }


  .feature-card {
    /* box-shadow: 26px 26px 52px #e0e0e0, -26px -26px 52px #ffffff; */
    border: 3px solid black;
    /* border-radius: 25px; */
    padding: 15px;
    display: grid;
    grid-template-columns: 1fr;
    grid-gap: 20px;
  }

  .feature-card p {
    font-size: 90%;
  }

  .feature-card div>* {
    padding: 5px;
  }

  .project-cta {
    grid-column: 1/-1;
    justify-content: center;

  }

  .project-cta a {
    color: #75928e;
    padding: 10px;
    font-size: 85%;
  }

  h4 {
    color: #e6d7d5;
    font-weight: 700;
  }

  img {
    height: auto;
    width: 100%;
    justify-self: center;
  }



  @media only screen and (min-width: 768px) {
    .cards {
      display: grid;
      grid-template-columns: 1fr 1fr;
      grid-gap: 30px;

    }

    img {
      max-width: 400px;

    }

  }
</style>