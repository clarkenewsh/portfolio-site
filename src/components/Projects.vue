<template>
  <section id="projects">
    <h2>My Projects__</h2>
    <p>A collection of projects I have been working on. I love to create passion projects to learn new rtechnology and improve my coding skills</p>
    <figure class="feature-card">
      <div>
        <h3 class="project-title">PopUps</h3>
        <h4 class="project-sub-title">Passion Project</h4>
        <p>PopUps Landing page was created on the back of the growing popularity of pop-up reatilers and cusine. The landing page was designed and coded using HTML5 and CC3.</p>
      </div>
      <img src="../assets/popups-thumb.png" alt="">
      <div class="project-cta">
        <a href="">View Site</a>
        <a href="">GitHub</a>
      </div>
    </figure>
    <figure class="feature-card">
      <div>
        <h3 class="project-title">DC Decorating Contractors Website</h3>
        <h4 class="project-sub-title">Passion Project</h4>
        <p>PopUps Landing page was created on the back of the growing popularity of pop-up reatilers and cusine. The landing page was designed and coded using HTML5 and CC3.</p>
      </div>
      <img src="../assets/popups-thumb.png" alt="">
      <div class="project-cta">
        <a href="">View Site</a>
        <a href="">GitHub</a>
      </div>
    </figure>
   <figure class="feature-card">
      <div>
        <h3 class="project-title">Landing Page Fashion Brand</h3>
        <h4 class="project-sub-title">Passion Project</h4>
        <p>PopUps Landing page was created on the back of the growing popularity of pop-up reatilers and cusine. The landing page was designed and coded using HTML5 and CC3.</p>
      </div>
      <img src="../assets/popups-thumb.png" alt="">
      <div class="project-cta">
        <a href="">View Site</a>
        <a href="">GitHub</a>
      </div>
    </figure>
   <figure class="feature-card">
      <div>
        <h3 class="project-title">Academic Course Tracker Web App</h3>
        <h4 class="project-sub-title">University Project</h4>
        <p>PopUps Landing page was created on the back of the growing popularity of pop-up reatilers and cusine. The landing page was designed and coded using HTML5 and CC3.</p>
      </div>
      <img src="../assets/popups-thumb.png" alt="">
      <div class="project-cta">
        <a href="">View Site</a>
        <a href="">GitHub</a>

      </div>
    </figure>
    
  </section>
</template>

<script>
  export default {
    name: 'Projects',
  }
</script>

<style scoped>

#projects {
  grid-column: 2;    
}

.feature-card {
  box-shadow: 26px 26px 52px #e0e0e0, -26px -26px 52px #ffffff;
  padding: 15px;
  border-top: 12px solid #ccd8d9;
  margin: 75px auto;
  max-width: 90%;
  display: grid;
  grid-template-columns: 1fr;
  grid-gap: 15px;
    
}

.project-cta {
  grid-column: 1/-1;
  text-align: right;
}

.project-cta a {
  color: #75928E;
  padding: 10px;
}

h4 {
  color: #e6d7d5;
  font-weight: 700;
}

img {
  height: auto;
  width: 100%;
  align-self: center;
}



  @media only screen and (min-width: 768px) {
    .feature-card {
      grid-template-columns: 1fr 1fr;
      padding: 25px;
    }

   
   
  }




  
</style>