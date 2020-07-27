<template>
   <footer>
     <ul>
       <li><i class="fab fa-github"></i></li>
       <li><i class="fab fa-bitbucket"></i></li>
       <li><i class="fab fa-twitter"></i></li>
       <li><i class="fas fa-envelope"></i></li>
     </ul>
     <p>Design and code by Me</p>
     <p>&copy; 2020 Clarke Newsham</p>

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


</style>