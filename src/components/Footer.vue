<template>
   <footer>
     <ul>
       <li>social 1</li>
       <li>social 2</li>
       <li>social 3</li>
       <li>social 4</li>
     </ul>
     <p>Design and code by Me</p>

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