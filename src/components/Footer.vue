<template>
   <footer>
     <ul>
       <li><a href="https://github.com/clarkenewsh"><i class="fab fa-github"></i></a></li>
       <li><a href="https://bitbucket.org/dashboard/repositories"><i class="fab fa-bitbucket"></i></a></li>
       <li><a href="https://www.linkedin.com/in/clarke-newsham/"><i class="fab fa-linkedin"></i></a></li>
       <li><a href = "mailto: clarke.newsham92@gmail.com"><i class="fas fa-envelope"></i></a></li>
     </ul>
     <p class="copyright">Design and code by  Clarke Newsham 2020 &copy;</p>
     <p></p>

   </footer>
</template>

<script>
  export default {
    name: 'Footer',
  }
</script>

<style scoped>

footer {
  height: 100px;
  grid-column: 2;
  border-top: 2px solid #ccd8d9 ;
  display: grid;
  grid-template-columns: 65% 35%;

}

footer ul {
  display: flex;
  flex-wrap: wrap;
  list-style: none;
}

footer ul li {
  padding: 20px;
}

footer p {
  padding: 20px;
}

.copyright {
  font-size: 70%;
}


</style>