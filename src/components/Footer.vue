<template>
  <footer>
    <div class="contact">
      <h3>Connect with me</h3>
      <p>Please feel free to hit me up and connect. I always try to make time for coffee and for meeting new people.</p>
      
    </div>
    <ul>
        <li><a href="https://github.com/clarkenewsh"><i class="fab fa-github"></i></a></li>
        <li><a href="https://bitbucket.org/dashboard/repositories"><i class="fab fa-bitbucket"></i></a></li>
        <li><a href="https://www.linkedin.com/in/clarke-newsham/"><i class="fab fa-linkedin"></i></a></li>
        <li><a href="mailto: clarke.newsham92@gmail.com"><i class="fas fa-envelope"></i></a></li>
      </ul>
    <p class="copyright">Design and code by Clarke Newsham 2021 &copy; &#9996;</p>
  </footer>
</template>

<script>
  export default {
    name: 'Footer',
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  footer {
    padding: 25px 10px;
    grid-column: 2;
    border-top: 6px solid #ccd8d9;

  }

  h3 {
    padding-bottom: 5px;
  }


  footer ul {
    display: flex;
    list-style: none;
    justify-content: space-between;
    padding: 20px;
    
  }

  footer ul li {
    padding: 15px 0px;

  }

  footer ul li a {
    color: #75928E;
    font-size: 140%;
  }

  .copyright {
    font-size: 70%;
    align-items: baseline;
    text-align: center;
  }

  @media only screen and (min-width: 768px) {

    footer {
      display: grid;
      grid-gap: 20px;
      grid-template-columns: 60% 40% 1fr;
    }

    .copyright {
      grid-column: 1/-1;
      grid-row: 2;
      text-align: left;
      padding: 10px 0px;
    }

    footer ul {
      justify-content: space-evenly;
    }
  }
</style>