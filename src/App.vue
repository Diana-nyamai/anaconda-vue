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
           <div class="left-inner">
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
          </div></div>

          <div class="right-container">
            <div class="right-inner">
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
            </div></div>
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
  height: 100vh;
  flex-wrap: wrap;
}
.right-container,
.left-container{
  position: relative;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 50%;
  flex-wrap: wrap;
  overflow: hidden;
}
.left-inner{
  width: 70%;
  position: absolute;
  right: 40px;
}
.left-content{
  display: flex;
  padding-bottom: 150px ;
  justify-content: flex-end;
}
.icon{
  padding-right: 20px; 
}
.text{
  width: 50%;
}


.right-inner{

    background: url('./assets/icon-bend.svg');
    height: 100vh;
    background-repeat: no-repeat;
    position: absolute;
    left: 0;
    width: 100%;
    display: flex;
    align-items: center;
}
.right-content{
  padding: 50px;
  position: absolute;
  left: 150px;
  background: #fff;
  width: 400px;
}
.right-content ul li{
  display: flex;
  line-height: 400%;
}
.right-content ul li i{
  padding-right: 10px;
}


@media all and (max-width: 768px){
.left-container,
.right-container{
  width: 100%;
}
.left-inner{
  width: 100%;
  right: 0;
}
.left-content{
  width: 100%;
  padding-bottom: 50px ;
  justify-content: center;
}
.text{
  width: 100%;
}

.right-inner{
  background: none;
}
.right-content{
  left: 0;
  justify-content: center;
}
}


</style>
