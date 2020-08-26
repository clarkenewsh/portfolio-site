<template>
  <section id="projects">
    <h2>My Projects__</h2>
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
          <a href="">View Site <i class="fas fa-globe-americas"></i></a>
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
          <a href="">View Site <i class="fas fa-globe-americas"></i></a>
          <a href="https://github.com/clarkenewsh/DC-Decorating-Services-Site">View on GitHub <i
              class="fab fa-github"></i></a>
        </div>
      </figure>
      <figure class="feature-card">
        <div>
          <h3 class="project-title">Fashion Brand landing page </h3>
          <h4 class="project-sub-title">Passion Project</h4>
          <p>PopUps Landing page was created on the back of the growing popularity of pop-up reatilers and cusine. The
            landing page was designed and coded using HTML5 and CC3.</p>
        </div>
        <img src="../assets/landing-fashion-thumb.png" alt="">
        <div class="project-cta">
          <a href="">View Site <i class="fas fa-globe-americas"></i></a>
          <a href="https://github.com/clarkenewsh/LandingPage-FashionMarketing">View on GitHub <i
              class="fab fa-github"></i></a>
        </div>
      </figure>
      <figure class="feature-card">
        <div>
          <h3 class="project-title">Academic Course Tracker Web App</h3>
          <h4 class="project-sub-title">University Project</h4>
          <p>PopUps Landing page was created on the back of the growing popularity of pop-up reatilers and cusine. The
            landing page was designed and coded using HTML5 and CC3.</p>
        </div>
        <img src="../assets/academic-track-thumb.png" alt="">
        <div class="project-cta">
          <a href="">View Site <i class="fas fa-globe-americas"></i></a>
          <a href="https://github.com/clarkenewsh/Academic-Tack-WebApp">View on GitHub <i class="fab fa-github"></i></a>
        </div>
      </figure>
      <figure class="feature-card">
        <div>
          <h3 class="project-title">SpaceX API App</h3>
          <h4 class="project-sub-title">Passion Project (Live prototype)</h4>
          <p>PopUps Landing page was created on the back of the growing popularity of pop-up reatilers and cusine. The
            landing page was designed and coded using HTML5 and CC3.</p>
        </div>
        <img src="../assets/popups-thumb.png" alt="">
        <div class="project-cta">
          <a href="">View Site <i class="fas fa-globe-americas"></i></a>
          <a href="https://github.com/clarkenewsh/SpaceX-WebApp">View on GitHub <i class="fab fa-github"></i></a>
        </div>
      </figure>
      <figure class="feature-card">
        <div>
          <h3 class="project-title">Europe in 35mm Website</h3>
          <h4 class="project-sub-title">Passion Project (Live prototype)</h4>
          <p>Inspired by a solo interail trip around Europe. A collection of 35mm photos taken while on my journey.
            Developed using CCS Grid and Netlify</p>
        </div>
        <img src="../assets/popups-thumb.png" alt="">
        <div class="project-cta">
          <a href="">View Site <i class="fas fa-globe-americas"></i></a>
          <a href="">View on GitHub <i class="fab fa-github"></i></a>
        </div>
      </figure>
      <figure class="feature-card">
        <div>
          <h3 class="project-title">CRUD App - Laravel and VueJS</h3>
          <h4 class="project-sub-title">Passion Project (Live prototype)</h4>
          <p>PopUps Landing page was created on the back of the growing popularity of pop-up reatilers and cusine. The
            landing page was designed and coded using HTML5 and CC3.</p>
        </div>
        <img src="../assets/popups-thumb.png" alt="">
        <div class="project-cta">
          <a href="">View Site <i class="fas fa-globe-americas"></i></a>
          <a href="">View on GitHub <i class="fab fa-github"></i></a>
        </div>
      </figure>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'Projects',
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #projects {
    grid-column: 2;
  }

  .cards {
    display: grid;
    grid-template-columns: 1fr;
    grid-row-gap: 70px;
    
    text-align: center;
  }


  .feature-card {
    box-shadow: 26px 26px 52px #e0e0e0, -26px -26px 52px #ffffff;
    padding: 15px;
    border-top: 12px solid #ccd8d9;
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