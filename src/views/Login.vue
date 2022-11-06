<template>
  <div class="login"></div>

  <main class="main">
    <section class="card-blue">
      <div class="itens">
        <h1>Login</h1>
        <div class="form">
          <span class="input">
            <img src="../assets/mail-outline.svg" alt="" />
            <input type="email" placeholder="E-mail" />
          </span>
          <span class="input">
            <img src="../assets/lock-closed-outline.svg" alt="" />
            <input type="password" placeholder="Senha" />
          </span>
          <span class="not-password">Esqueceu a senha?</span>
          <a class="button-entry" href="#">Entrar</a>
        </div>
      </div>
    </section>
    <section class="rafiki">
      <img src="../assets/Privacy-policy-rafiki-2.svg" alt="" />
    </section>
  </main>
</template>

<script>
export default {
  name: "login",
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

* {
  margin: 0;
  padding: 0;
  font-family: "Poppins", sans-serif;
  text-decoration: none;
  list-style: none;
}

.main {
  display: flex;
}

.card-blue {
  background-color: #3c60a6;
  width: 30rem;
  height: 750px;
}

.itens {
  display: block;
  align-items: center;
  flex-direction: column;   
}

.itens h1 {
  color: #3fee9e;
  margin: 6.5625rem 23.375rem 2.5rem 2.25rem;
  font-weight: 700;
  font-size: 32pt;
}

.form {
  display: block;
  margin-left: 2.25rem;
}

.input {
  display: flex;
  background: #e3e3e3;
  height: 3rem;
  border-radius: .6rem;
  margin-bottom: 1.5rem;
  max-width: 23rem;
}

.input img {
  width: 1.25rem;
  padding-left: 0.625rem;
}

.input input {
  display: block;
  background: none;
  border: hidden;
  padding-left: 2.5rem;
  margin-left: -1.875rem;
  border-radius: 0.6rem;
  width: 15rem;
}

.input input:focus {
  outline: none;
}

.not-password {
  display: flex;
  align-items: flex-start;
  margin-top: 1.5rem;
  margin-bottom: 3.25rem;
  color: #fff;
  font-size: 10pt;
}

.button-entry {
  display: flex;
  justify-content: center;
  margin-left: 22%;
  background: #6464ac;
  border: 0.1875rem solid #343c54;
  width: 11.25rem;
  height: 3.75rem;
  align-items: center;
  color: #fff;
  font-weight: 900;
  font-size: 18pt;
  box-shadow: 0rem 0.25rem 0.25rem rgba(0, 0, 0, 0.25);
  border-radius: 1.25rem;
}

.rafiki {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 70vw;
}

.rafiki img {
  min-width: 50vw;
  margin-top: -4px;
}
</style>