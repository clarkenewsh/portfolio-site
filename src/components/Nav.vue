<template>
  <nav>
    <ul>
      <li><a id="brand" href="#">Portfolio</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="https://github.com/clarkenewsh">GitHub</a></li>
      <li><a class="download-cta-button" href="">Download Resume</a></li>
    </ul>
  </nav>
</template>

<script>
  export default {
    name: 'Nav',
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  nav {
    color: black;
    grid-column: 2;
    background: white;
    padding: 20px 0px;
  }

  nav ul li:first-child {
    margin-right: auto;
    /* splits the logo right from the navigation*/
  }

  nav ul {
    list-style: none;
    display: flex;
    flex-wrap: wrap;
  }

  nav ul li {
    padding: 10px;
  }

  nav ul li a {
    color: black;
    text-decoration: none;
  }


  nav ul li a:hover,
  li:active {
    color: gray;
  }

  #brand {
    color: black;
    text-decoration: none;
    font-weight: 900;
    margin-right: auto;
    font-size: 105%;
  }

  .download-cta-button {
    background: black;
    color: white;
    padding: 10px;
    border: 2px solid black;
    border-radius: 50px;
    font-weight: 700;
    font-size: 70%;
  }

  .download-cta-button:hover,
  .download-cta-button:active {
    background: white;
    color: black;
  }

  @media only screen and (min-width: 768px) {

    .download-cta-button {
      padding: 15px 20px;
    }


 }
</style>