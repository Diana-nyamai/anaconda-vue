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
    <div class="services-container">
          <div class="left-container">
           
            <div class="left-content">
            <div class="icon">icon</div>
            <div class="text">
              <h3>Tackle any challenge</h3>
              <p>Anaconda solutions are serious technology for real data science and ML applications. Anaconda is versatile - you'll be ready to solve problems you don't even know you have yet.</p>
            </div>
          </div>
          <div class="left-content">
            <div class="icon">icon</div>
            <div class="text">
              <h3>Tackle any challenge</h3>
              <p>Anaconda solutions are serious technology for real data science and ML applications. Anaconda is versatile - you'll be ready to solve problems you don't even know you have yet.</p>
            </div>
          </div>
          <div class="left-content">
            <div class="icon">icon</div>
            <div class="text">
              <h3>Tackle any challenge</h3>
              <p>Anaconda solutions are serious technology for real data science and ML applications. Anaconda is versatile - you'll be ready to solve problems you don't even know you have yet.</p>
            </div>
          </div>
          </div>

          <div class="right-container">
            <div class="right-content">
              <div class="header1"><h3>Why it matters</h3></div>
              <ul>
                <li>
                  <i>icon</i>
                  <p>Deliver on your data strategy</p>
                </li>
                 <li>
                  <i>icon</i>
                  <p>Deliver on your data strategy</p>
                </li>
                 <li>
                  <i>icon</i>
                  <p>Deliver on your data strategy</p>
                </li>
                 <li>
                  <i>icon</i>
                  <p>Deliver on your data strategy</p>
                </li>
              </ul>
            </div>
          </div>
    </div>
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

/* services */
.services-container{
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  flex-wrap: wrap;
  overflow: hidden;
}
.left-container,
.right-container{
  position: relative;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 50%;
  flex-wrap: wrap;
}
.left-content{
  display: flex;
  width: 50%;
  padding-bottom: 150px;
}
.right-container{
  background-image: url('./assets/icon-bend.svg');
  background-repeat: no-repeat;
  
}
@media all and (max-width: 768px){
  .left-container,
.right-container{
  width: 100%;
}
.left-content{
  width: 100%;



  
}
}
.right-container{
  background-image: none;
}


</style>
