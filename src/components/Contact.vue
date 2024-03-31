<template>
    <div class="contact-container">
      <h4>Personal Information</h4>
      <div class="contact-info">
        <div class="contact-column">
          <p><strong>Name:</strong> Gina Olpos</p>
          <p><strong>Gender:</strong> Female</p>
          <p><strong>Birthdate:</strong>December 19 1999</p>
          <p><strong>Age:</strong> 22</p>
        </div>
        <div class="contact-column">
          <p><strong>Address:</strong> Ibabao Cordova Cebu</p>
          <p><strong>School: </strong> Cordova Public College</p>
          <p><strong>Course: </strong> Bachelor of Science and Information Technology</p>
          <p><strong>Email Address:</strong> olposgina@gmail.com</p>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  .contact-container {
    margin: 10%; 
    display: flex;
    flex-direction: column;
    align-items: flex-start; 
    text-align: left; 
    background-image: url('@/assets/background.png'); 
    background-size: cover; 
    background-repeat: no-repeat; 
    padding: 200px; 
    border-radius: 10px; 
    color: #333; 
  }
  
  .contact-info {
    display: flex;
    flex-direction: column; 
    gap: 20px; 
  }
  
  .contact-column {
    flex: 1;
  }
  </style>
  
  
  
  
  