<template>
  <nav class="navbar">
    <div class="container">
      <div class="logo">LearnlyApp</div>
      <ul class="nav-links">
        <li><a href="#">For Creators</a></li>
        <li><a href="#">For Learners</a></li>
        <li><a href="#">Pricing</a></li>
        <li><a href="#">Blogs</a></li>
      </ul>
      <div class="auth-buttons">
        <button class="login-btn">Log in</button>
        <button class="signup-btn">Sign Up</button>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'MainNavbar'
}
</script>

<style scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 40px;
  background: white;
  box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
}
.logo {
  font-size: 22px;
  font-weight: bold;
}
.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}
.nav-links a {
  text-decoration: none;
  color: black;
}
.auth-buttons button {
  margin-left: 10px;
  padding: 8px 15px;
  border-radius: 5px;
  border: none;
}
.login-btn {
  background: none;
  border: 1px solid black;
}
.signup-btn {
  background: #3b82f6;
  color: white;
}
</style>