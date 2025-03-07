<template>
    <section class="hero">
      <div class="hero-text">
        <h1>Turn your <span class="highlight">content</span> into interactive learning.</h1>
        <p>
          Upload your course contents and let LearnlyAI transform them into engaging, 
          gamified experiences that captivate learners and boost retention.
        </p>
        <button class="cta-btn">Get Started Now</button>
      </div>
      <div class="hero-image">
        <img src="@/assets/HeroImage.jpeg" alt="Student Learning">
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: "HeroSection",
  };
  </script>
  
  <style scoped>
  .hero {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 80px 60px;
  }
  
  .hero-text {
    max-width: 50%;
  }
  
  .hero-text h1 {
    font-size: 40px;
    font-weight: bold;
    margin-bottom: 20px;
  }
  
  .highlight {
    color: #001f8f;
  }
  
  .hero-text p {
    font-size: 18px;
    line-height: 1.6;
    margin-bottom: 20px;
  }
  
  .cta-btn {
    background: #3b82f6;
    color: white;
    border: none;
    padding: 12px 20px;
    border-radius: 5px;
    font-size: 18px;
    cursor: pointer;
  }
  
  .cta-btn:hover {
    background: #2563eb;
  }
  
  .hero-image img {
    width: 450px;
    border-radius: 10px;
  }
  </style>
  