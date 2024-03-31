<template>
    <div id="home" class="pink-bg">
      <div class="container">
        <div class="content">
          <h1>Hello, I'm Gina</h1>
          <div class="animated-picture"></div>
          <p>Welcome to My Portfolio Website
            <br> I am passionate about in designing web
            <br> and I also studied graphic design.
          </p>
          <p class="name">BSIT Student</p> <!-- Add the name -->
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  #home {
    height: 100vh;
    width: 100vw; 
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden; 
  }
  
  .container {
    text-align: center;
  }
  
  .content {
    display: inline-block; 
    vertical-align: middle; 
    margin-right: 20px; 
  }
  
  .animated-picture {
    width: 200px;
    height: 200px;
    background-image: url('@/assets/gin.jpg');
    background-size: cover;
    background-position: center;
    border-radius: 50%;
    animation: stationary 4s linear infinite; 
  }
  
  @keyframes stationary {
    0% {
      transform: rotate(0deg);
    }
    100% {
      transform: rotate(0deg); 
    }
  }
  
  
  .name {
    animation: eraseName 5s linear infinite; 
  }
  
  @keyframes eraseName {
    0% {
      opacity: 1;
    }
    100% {
      opacity: 0; /* Gradually reduce opacity to make the name disappear */
    }
  }
  
  
  .name {
    margin-top: 20px; /* Adjust the margin as needed */
  }
  
  /* Background image */
  .pink-bg {
    background-image: url('@/assets/rose.jpg'); 
    background-size: cover; 
    background-position: center; 
    margin: 0; 
    padding: 0; 
  }
  </style>
  
  