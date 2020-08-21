<template>
  <footer>
    <div class="contact">
      <h3>Connect with me</h3>
      <p>Please feel free to hit me up via email, I always try to make time for coffee and for meeting new people. I’m
        also on Instagram, LinkedIn, Dribbble, Twitter</p>
      <ul>
        <li><a href="https://github.com/clarkenewsh"><i class="fab fa-github"></i></a></li>
        <li><a href="https://bitbucket.org/dashboard/repositories"><i class="fab fa-bitbucket"></i></a></li>
        <li><a href="https://www.linkedin.com/in/clarke-newsham/"><i class="fab fa-linkedin"></i></a></li>
        <li><a href="mailto: clarke.newsham92@gmail.com"><i class="fas fa-envelope"></i></a></li>
      </ul>
    </div>

    <p class="copyright">Design and code by Clarke Newsham 2020 &copy;</p>

  </footer>
</template>

<script>
  export default {
    name: 'Footer',
  }
</script>

<style scoped>
  footer {
    padding: 10px 10px;
    grid-column: 2;
    border-top: 6px solid #ccd8d9;

  }


  footer ul {
    display: flex;
    flex-wrap: wrap;
    list-style: none;
    justify-content: space-between;
    padding: 10px;
  }

  footer ul li {
    /* padding: 25px; */

  }

  footer ul li a {
    color: #75928E;
    font-size: 130%;
  }


  .copyright {
    font-size: 70%;
    align-items: baseline;
  }

  @media only screen and (min-width: 768px) {

    footer {
      display: grid;
      grid-template-columns: 65% 35%;
    }

  }
</style>