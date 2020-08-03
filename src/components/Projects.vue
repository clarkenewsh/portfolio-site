<template>
  <section id="projects">
    <h2>My Projects__</h2>
    <div class="card"></div>
    <figure class="feature-card">
        <h3>PopUps</h3>
        <h4>Passion Project</h4>
        <p>PopUps Landing page was created on the back of the growing popularity of pop-up reatilers and cusine. The landing page was designed and coded using HTML5 and CC3. </p>
        <img src="../assets/popups-project.png" alt="">
        <div class="project-cta">
          <a href="">View Site</a>
          <a href="">GitHub</a>
          <a href="">Read more</a>
        </div>
    </figure>
    <figure class="feature-card">
        <h3>UX Design re-design Study E-learning Environments</h3>
        <h4>University Project</h4>
        <p>Description of the project and the technologies used to develop it will go here</p>
        <img src="" alt="">
        <a href="">Link to the hosted netlify site</a>
        <a href="">Link to github with icons here</a>
        <a href="">Read more> this will take you to the project id/1 route... need to discover vue routing</a>

    </figure>
    <figure class="feature-card">
        <h3>DC Decorating Contractors Website</h3>
        <p>Description of the project and the technologies used to develop it will go here</p>
        <img src="" alt="">
        <a href="">Link to the hosted netlify site</a>
        <a href="">Link to github with icons here</a>
        <a href="">Read more> this will take you to the project id/1 route... need to discover vue routing</a>

    </figure>
    <figure class="feature-card">
        <h3>Landing Page - Fashion Sector</h3>
        <p>Description of the project and the technologies used to develop it will go here</p>
        <img src="" alt="">
        <a href="">Link to the hosted netlify site</a>
        <a href="">Link to github with icons here</a>
        <a href="">Read more> this will take you to the project id/1 route... need to discover vue routing</a>

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
    border-top: 8px solid #ccd8d9;
    border-radius: 5px;
    margin: 75px 0px;
    
}

  h2 {
    font-size: 150%;
    font-weight: 900;
    
  }

.feature-card:nth-of-type(1) {
  margin: 0 auto;
}

.feature-card:nth-of-type(2) {
  margin-left: auto;
}

.feature-card:nth-of-type(3) {
  margin-right: auto;
}

.feature-card:nth-of-type(4) {
  margin: 0 auto;
}

img {
    width: 240px;
    height: 160px;
}


h4 {
    color: #e6d7d5;
    font-weight: 700;
}



  
</style>