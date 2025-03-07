<template>
    <section class="personality">
      <h2>Discover Your Learning Personality</h2>
      <p>Take our quick personality test to find out which learning method suits you best. We’ve got the perfect gamification style for all personalities.</p>
      <button>Start the Test</button>
    </section>
  </template>
  
  <script>
  export default {
    name: 'LearningPersonality'
  }
  </script>
  
  <style scoped>
  .personality {
    text-align: center;
    padding: 2rem;
    background-color: #f8f9fa;
  }
  button {
    padding: 0.5rem 1rem;
    background-color: #28a745;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  </style>