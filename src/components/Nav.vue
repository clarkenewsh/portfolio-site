<template>
   <nav>
       <ul> 
           <li><a id="brand" href="#">Portfolio</a></li>
           <li><a href="#projects">Projects</a></li>
           <li><a href="https://github.com/clarkenewsh">GitHub</a></li>
           <li><a href="">Resume</a></li>
       </ul>
   </nav>
</template>

<script>
  export default {
    name: 'Nav',
  }
</script>

<style scoped>

nav {
    color: black;
    grid-column: 2;
    padding: 20px 0px;

}

nav ul li:first-child {
    margin-right: auto; /* splits the logo right from the navigation*/
}

nav ul {
    list-style: none;
    display: flex;
    
}

nav ul li { 
    padding: 10px;
}
nav ul li a {
    color: black;
    text-decoration: none;
}


nav ul li:hover, li:active {
  color: gray;
  cursor: pointer;
  
}


#brand {
  color: black;
  text-decoration: none;
  font-weight: 900;
  margin-right: auto;
}



</style>