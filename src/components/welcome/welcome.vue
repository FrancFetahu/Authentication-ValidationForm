<template>
  <div id="welcome">
    <h1>Create an account or log into Website.</h1>
    <p>You found the best place to have fun - and now you're just one sign in (or sign up) away from it!</p>
    <div class="cta">
      <router-link to="/signup">Sign Up</router-link>
      <router-link to="/signin">Sign In</router-link>
    </div>
  </div>
</template>

<style scoped>
#welcome {
  width: 80%;
  margin: auto;
}

h1 {
  text-align: center;
}

p {
  text-align: center;
}

.cta {
  width: 300px;
  margin: auto;
  text-align: center;
}

.cta a {
  margin: 10px;
  text-decoration: none;
  display: inline-block;
  border: 1px solid #09300b;
  border-radius: 3px;
  width: 100px;
  padding: 10px;
  box-sizing: border-box;
  color: #09300b;
}

.cta a:hover,
.cta a:active {
  background-color: #09300b;
  color: white;
}
</style>