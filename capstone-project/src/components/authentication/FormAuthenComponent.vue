<script setup></script>

<template>
  <div class="wrapper">
    <form action="">
      <h1>Login</h1>
      <div class="input-box">
        <input type="text" placeholder="Username" required />
        <i class="bx bxs-user"></i>
      </div>
      <div class="input-box">
        <input type="password" placeholder="Password" required />
        <i class="bx bxs-lock-alt"></i>
      </div>
      <div class="remember-forgot">
        <label><input type="checkbox" />Remember Me</label>
        <a href="#">Forgot Password</a>
      </div>
      <button type="submit" class="btn">Login</button>
      
    </form>
  </div>
</template>

<style>
@import "../../assets/styles/authentication/components/formComponent.scss"
</style>