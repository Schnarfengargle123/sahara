<template>
  <div class="login">
    <img class="logo" alt="Vue logo" src="../assets/Sahara.png">
    <h1>Welcome to Sahara</h1>
    <h3>Login or Sign Up</h3>
    <form class="login__form" id="login">
      <label for="email">Email</label>
      <input
        type="email"
        name="email"
        id="email"
        placeholder="user@email.com"
      />
      <label for="password">Password</label>
      <input
        type="password"
        name="password"
        id="password"
        placeholder="**********"
      />
      <div class="login__form__submit-buttons">
        <span class="buttonUp" id="login__submit-buttons__login"><button type="submit">Login</button></span>
        <span class="buttonUp"><button type="submit">Sign Up</button></span>
      </div>
    </form>
    <p>Copyright &copy; Sahara 2021</p>
  </div>
</template>

<script>
// export default {
//   name: "LoginForm",
//   component: {
//     Login
//   }
// };

// const login = document.getElementById("login");
// const button = document.getElementById("login__submit-buttons__login");
// const loginErrorMsg = document.getElementById("")
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* font-family: 'Quicksand', sans-serif; */

h3 {
  margin: 40px 0 0;
}

/* ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
} */

.login {
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.login__form {
  height: 17rem;
  width: 10rem;
  margin-top: 2.5rem;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: flex-start;
}

.login input {
  padding: 0.5rem;
  border-style: none;
  border-radius: 0.2rem;
  box-shadow: 0rem 0.1rem 0.2rem 0.1rem slategray;
  transition: box-shadow, tranform 100ms;
  transition-delay: 50ms;
}

.login input:hover {
  box-shadow: 0rem 0.1rem 0.3rem 0.15rem slategray;
  transform: translateY(-0.05rem);
}

.login__form__submit-buttons {
  width: 100%;
  height: 5rem;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
}

.login__form__submit-buttons button {
  width: 4rem;
  height: 2.5rem;
  border-style: none;
  border-radius: 0.2rem;
  box-shadow: 0rem 0.1rem 0.1rem 0.0rem slategray;
  transition: box-shadow, transform 100ms;
  transition-delay: 50ms;
  color: rgb(68, 83, 90);
  background-color: coral;
}

 .login__form__submit-buttons button:hover {
  box-shadow: 0rem 0.1rem 0.3rem 0.1rem slategray;
  background-color: rgb(186, 212, 224);
  transform: translateY(-0.5rem);
  color: rgb(252, 100, 45);
  cursor: pointer;
  width: 4.1rem;
  height: 2.6rem;
}

.login__form__submit-buttons button:focus {
  outline: 0;
}
</style>
