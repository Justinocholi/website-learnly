<template>
  <footer>
    <div class="footer-links">
      <a href="#">FAQs</a>
      <a href="#">About Us</a>
      <a href="#">Terms of Service</a>
      <a href="#">Privacy Policy</a>
      <a href="#">Cookie Policy</a>
    </div>
    <p>©2025 LearnlyApp - Technify Incubator. All rights reserved</p>
  </footer>
</template>

<script>
export default {
  name: 'AppFooter'
}
</script>

<style scoped>
footer {
  text-align: center;
  padding: 1rem;
  background-color: #f8f9fa;
}
.footer-links {
  margin-bottom: 1rem;
}
.footer-links a {
  margin: 0 1rem;
  text-decoration: none;
  color: #007bff;
}
</style>