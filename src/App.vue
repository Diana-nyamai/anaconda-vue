<template>
  <div>
    <header>
       <!-- <Navbar/> -->
    </header>

    <!-- body -->
    <div class="second-section">
      <div class="title-container">
      <div class="title">
        <h1>Not just</h1>
        <h1>point solutions.</h1>
        <h1 class="green">Powerful solving.</h1>
        <p>Anaconda was built by data scientists, for data scientists. More than 20 million people use our technology to solve the toughest problems.</p>
      </div></div>

    </div><!-- second section -->
  </div><!-- enclosing the entire page -->
</template>

<script>
// import  Navbar from './components/Navbar.vue';


export default {
  name: 'App',
  components: {
    //  Navbar
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

/* second section */
.second-section{
  height: auto;
  padding: 10px;
  width: 100%;
  background: #dcf0ef;
}
.title-container{
  width: 100%;
  display: flex;
  justify-content: center;
  padding: 100px;
}
.title{
  position: relative;
  left: 100px;
}
.title h1{
  line-height: 1.1em;
  font-weight: 300;
  font-size: 3.4rem;
}
.title .green{
  color: #43b049;
}
.title p{
  line-height: 1.8em;
  font-weight: 300;
  color: #556575;
  font-size: 1.125rem;
  width: 60%;
}
@media all and (max-width: 1000px){
  .title{
    left: 0;
  }
  .title-container{
    padding: 20px;
  }
  .title h1{
    font-size: 2.5rem;
  }
  .title p {
    width: 100%;
  }
}



</style>
