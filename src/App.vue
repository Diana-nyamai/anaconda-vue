<template>
  <div>
    <header>
       <Navbar/>
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

      <div class="m-container">
        <div class="left">
          <div class="left-outer">
          <div class="left-inner">
            <div class="left-icon">icon</div>
            <div class="right-text">
              <h4>Tackle any challenge</h4>
              <p>Anaconda solutions are serious technology for real data science and ML applications. Anaconda is versatile - you'll be ready to solve problems you don't even know you have yet.</p>
            </div>
            </div>
             <div class="left-inner">
            <div class="left-icon">icon</div>
            <div class="right-text">
              <h4>Tackle any challenge</h4>
              <p>Anaconda solutions are serious technology for real data science and ML applications. Anaconda is versatile - you'll be ready to solve problems you don't even know you have yet.</p>
            </div>
            </div>
             <div class="left-inner">
            <div class="left-icon">icon</div>
            <div class="right-text">
              <h4>Tackle any challenge</h4>
              <p>Anaconda solutions are serious technology for real data science and ML applications. Anaconda is versatile - you'll be ready to solve problems you don't even know you have yet.</p>
            </div>
            </div></div>
        </div>

        <div class="right">
          <div class="right-box">
             <div class="right-card">
               <div class="r-title"><h2>Why it matters</h2></div>
               <ul>
                 <li>
                   <i>tick</i>
                   <p>Deliver on your data strategy</p>
                 </li>
                  <li>
                   <i>tick</i>
                   <p>Get to market faster</p>
                 </li>
                  <li>
                   <i>tick</i>
                   <p>Maximize flexibility and control</p>
                 </li>
                  <li>
                   <i>tick</i>
                   <p>Attract and keep the best talent</p>
                 </li>
               </ul>
             </div></div>
        </div>
      </div>
  <div class="bottom-container">
  <div class="bottom-content">
    <p>The modern world of data science is incredibly dynamic. Every day, new challenges surface - and so do incredible innovations. To win in this context, organizations need to give their teams the most versatile, powerful data science and machine learning technology so they can innovate fast - without sacrificing security and governance.</p>
    <p>We call that powerful solving.</p>
  </div></div>
    </div>
    
  </div><!-- enclosing the entire page -->
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

/* second section */
.second-section{
  height: auto;
  width: 100%;
  background: #dcf0ef;
}
.title-container{
  width: 100%;
  display: flex;
  justify-content: center;
  padding: 100px;
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

.m-container{
  width: 100%;
  height: auto;
  display: flex;
  justify-content: center;
  align-content: center;
}
.left{
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-end;
}
.left-outer{
  width: 50%;
}
.left-inner{
  display: flex;
  margin: 120px 0;
}
.left-icon{
  padding: 0 20px;
}
.right-text{
  font-size: 18px;
}
.right-text p{
  color: #556575;
}
 .right{
   background-image: url(./assets/icon-bend.svg);
   width: 100%;
   height: 100vh;
   background-repeat: no-repeat;
   display: flex;
   justify-content:flex-start;
   align-items: center;
   padding: 0 150px;
 }

 .right-card{
   padding: 20px;
  background: white;
  color: #000;
  padding: 80px;
 }
 .r-title h2{
   text-align: center;
   font-weight: 300;
   font-size: 2.6em;
   margin-bottom: 1em;
 }
 .right-card ul li{
   display: flex;
   line-height: 400%;
   font-weight: 600;
 }
 .right-card ul li i{
   padding-right:10px;
 }
 .bottom-container{
   display: flex;
   justify-content: flex-end;
   width: 50%;
   
   border: 1px solid black;
 }
 .bottom-content{
   border: 1px solid black;
   width: 60%;
   font-size: 20px;
   color: #556575;
 }
</style>
