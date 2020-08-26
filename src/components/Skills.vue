<template>
  <section id="skills">
    <h2>My Design and Dev Tootkit__</h2>
    <p>My web tookit I hear you ask. My webtool kit is a collection of my knowlege around design, user exeperience
      design and web developement (front and back end). These are the tools (my knowlwge) I will carry into any UX or
      developement project</p>
    <h3>UX Design</h3>
    <ul>
      <li>User Research</li>
      <li>Qualitative and Quantitative Reserach methods</li>
      <li>UI Design</li>
      <li>Usability Testing (A/B Testing, lab testing, remote testing)</li>
      <li>Prototyping</li>
      <li>Wireframes</li>
      <li>User Personas</li>
      <li></li>
    </ul>
    <h3>Development</h3>
    <ul>
      <li>HTML5 and CSS3</li>
      <li>Vanilla JS and jQuery</li>
      <li>PHP with Laravel Framework</li>
      <li>JavaScript Framework - VueJS</li>
      <li>CRUD Apps</li>
      <li>MVC Architecture</li>
    </ul>
    <p>Please find out more about my skills and work experiences and <a href="">View My Resume</a></p>
  </section>
</template>

<script>
  export default {
    name: 'Skills',

  }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #skills {
    grid-column: 2;
  }

  @media only screen and (min-width: 768px) {
    #skills {}
  }
</style>