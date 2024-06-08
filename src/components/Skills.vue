<!-- src/components/Skills.vue -->
<template>
    <section>
      <h2>Skills</h2>
      <ul>
        <li v-for="(skill, index) in skills" :key="index">{{ skill }}</li>
      </ul>
    </section>
  </template>
  
  <script>
  export default {
    name: 'Skills',
    data() {
      return {
        skills: ['HTML', 'CSS', 'JavaScript', 'Vue.js', 'Git', 'GitHub', 'React.js', 'Ai']
      }
    }
  }
  </script>
  
  <style scoped>
  section {
    padding: 20px;
    text-align: center;
  }
  
  ul {
    list-style: none;
    padding: 0;
  }
  
  li {
    display: inline-block;
    margin: 5px 10px;
    padding: 5px 10px;
    background: #34b4df;
    color: #fff;
    border-radius: 5px;
  }
  </style>
  