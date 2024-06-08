<!-- src/components/Header.vue -->
<template>
    <header>
      <nav>
        <ul>
          <li><router-link to="/">Home</router-link></li>
          <li><router-link to="/about">About</router-link></li>
          <li><router-link to="/projects">Projects</router-link></li>
          <li><router-link to="/skills">Skills</router-link></li>
          <li><router-link to="/contact">Contact</router-link></li>
        </ul>
      </nav>
    </header>
  </template>
  
  <script>
  export default {
  name: 'Header'
  }
  </script>
  
  <style scoped>
  header {
    background: #34b4df;
    color: #fff;
    padding: 10px 0;
  }
  
  nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0;
    margin: 0;
  }
  
  nav ul li {
    margin: 0 15px;
  }
  
  nav ul li a {
    color: #fff;
    text-decoration: none;
  }
  </style>
  