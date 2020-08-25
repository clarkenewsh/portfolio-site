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

<style scoped>

nav {
  color: black;
  grid-column: 2;
  background: white;
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


nav ul li a:hover, li:active {
  border-bottom: 3px solid #ccdbd9;
  cursor: pointer; 
}

#brand {
  color: black;
  text-decoration: none;
  font-weight: 900;
  margin-right: auto;
}

.download-cta-button {

  background: white;
  color: black;
  padding: 15px;
  border: 2px solid black;
  border-radius: 50px;
  font-weight: 700;
  font-size: 70%;
}

.download-cta-button:hover,
.download-cta-button:active
  {
  background: black;
  color: white;
}



</style>