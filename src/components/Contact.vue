<template>
    <section>
      <h2>Contact Me</h2>
      <label>Email:</label>  <a href=""> chiekwenachidera@gmail.com</a> 
       <p> <label>Mobile:</label> 08138134923 </p> 
     
    </section>
  </template>
  
  <script>
  import emailjs from 'emailjs-com';
  
  export default {
    name: 'Contact',
    data() {
      return {
       
      }
    },
  }
  </script>
  
  <style scoped>
  section {
    padding: 20px;
    text-align: center;

  }
  
  a, p, label {
    color: #fff;
    font-weight: bolder;
  }

  </style>
  