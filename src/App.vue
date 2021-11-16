<template>
  <div>
    <header>
       <Navbar/>
    </header>
  </div>
</template>

<script>
import  Navbar from './components/Navbar.vue';


export default {
  name: 'App',
  components: {
     Navbar
  }
  
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body{
  font-family: 'Montserrat', sans-serif;
  font-weight: 500;
  line-height: 1.5rem;
  overflow-x: hidden;
}
header{
  width: 100vw;
  background: white;
  color: black;
  padding: 30px;
}
a{
  color: black;
  text-decoration: none;
}
</style>
