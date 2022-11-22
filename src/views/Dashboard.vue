<template>
  <main>
    <div>
      <div class="container">
        <button class="btn-card">Home</button>
        <button class="btn-card">Desafios</button>
        <button class="btn-card">Respostas</button>
        <button class="btn-card">Seus Desafios</button>
      </div>
    </div>

    <div class="postArea">
      <div class="wrapper">
        <div class="input-box">
          <div class="post-card">
            <input type="text" class="input" placeholder="Digite algo..." />
            <input type="submit" class="btn" value="Postar" />
          </div>
        </div>
      </div>
      <div class="userPost">
        <div class="userInfo">
          <div class="user">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              style="fill: #fff; transform: ; msfilter: "
            >
              <path
                d="M12 2C6.579 2 2 6.579 2 12s4.579 10 10 10 10-4.579 10-10S17.421 2 12 2zm0 5c1.727 0 3 1.272 3 3s-1.273 3-3 3c-1.726 0-3-1.272-3-3s1.274-3 3-3zm-5.106 9.772c.897-1.32 2.393-2.2 4.106-2.2h2c1.714 0 3.209.88 4.106 2.2C15.828 18.14 14.015 19 12 19s-3.828-.86-5.106-2.228z"
              ></path>
            </svg>
            <p>user20442</p>
          </div>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            style="fill: #fff; transform: ; msfilter: "
          >
            <path
              d="M12 10c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zm6 0c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2zM6 10c-1.1 0-2 .9-2 2s.9 2 2 2 2-.9 2-2-.9-2-2-2z"
            ></path>
          </svg>
        </div>
        <div class="infoTextPost">
          <p>
            Lorem ipsum, or lipsum as it is sometimes known, is dummy text used
            in laying out print, graphic or web designs. The passage is
            attributed to an unknown ...
          </p>
        </div>
        <div class="imgPostUser">
          <img src="../assets/C_Hello_World_Program.png" alt="" />
        </div>
        <div class="buttons">
            <button class="btnAction">Comentar</button>
            <button class="btnAction">Solucionar</button>
          </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "dashboard",
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

:root {
  --text-shadow: 0rem 0.25rem 0.25rem rgba(0, 0, 0, 0.25);
}

* {
  margin: 0;
  padding: 0;
  font-family: "Poppins", sans-serif;
  text-decoration: none;
  list-style: none;
  color: #fff;
}

.postArea {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-left: 2rem;
  margin-top: 5rem;
  width: 60%;
  height: 100vh;
  
}

.userPost {
  background: #2e2e2e;
  width: 435px;
  /* height: 516px; */
  box-shadow: 1rem 1rem 1.75rem rgba(0, 0, 0, 0.25);
  border-radius: 1rem;
}

.userInfo {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0.25rem;
}

.user {
  display: flex;
  align-items: center;
  padding: 0.25rem;
  width: 80%;
}
.user p,
.user svg {
  margin-left: 0.5rem;
  cursor: pointer;
}

svg {
    width: 2rem;
    height: auto;
}

.infoTextPost {
  margin: 1rem;
  text-align: start;
  font-size: 9pt;
}

.imgPostUser {
  margin-bottom: 1rem;
}

.imgPostUser img {
  width: 98%;
}

.buttons {
  display: flex;
  justify-content: space-around;
  border-top: .0625rem solid #808080;
  border-bottom: .0625rem solid #808080;
  margin-bottom: 1rem;
}

.btnAction {
  width: 10.4375rem;
  height: 2rem;
  background: rgba(0, 0, 0, 0.4);
  box-shadow: 0.25rem 0.25rem 0.25rem rgba(0, 0, 0, 0.25);
  border-radius: 1rem;
  cursor: pointer;
  margin: 0.5rem;
}

.btnAction:hover {
    transition: 0.2s;
    background: rgba(31, 31, 31, 0.4);
    transform: scale(1.05);
}

h1 {
  color: #000;
}

main {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  /* border: 2px solid red; */
}

.wrapper {
  background: #212121;
  box-shadow: 6px 4px 5px rgba(0, 0, 0, 0.25);
  min-width: 50%;
  border-radius: 20px;
  width: 40%;
  border-radius: 15px;
  padding: 25px 25px 15px 25px;
  margin-bottom: 2rem;
}

.input-box {
  padding-top: 20px;
}

.input-box .post-card {
  position: relative;
  min-height: 120px;
  max-height: 150px;
}

.post-card .input {
  background: transparent;
  border: none;
  font-size: 16px;
}

.post-card .btn {
  width: 123px;
  height: 49px;
  background: #1da1f2;
  border-radius: 74px;
  font-weight: 500;
  font-size: 24px;
  line-height: 29px;
  border: none;
  outline: none;
  margin-left: 15%;
}

.post-card .btn:hover {
  background: #185d88;
  cursor: pointer;
}

.container {
  left: 0;
  top: 0;
  width: 20%;
  height: 100%;
  background-color: #3c60a6;
  position: fixed;
}

.btn-card {
  background-color: #6464ac;
  width: 60%;
  height: 5%;
  display: flex;
  justify-content: space-around;
  border: none;
  font-size: 1.2em;
  margin-left: 20%;
  margin-top: 20%;
  cursor: pointer;
  border-radius: 16px;
  box-shadow: rgba(0, 0, 0, 0.15) 1.95px 1.95px 2.6px;
}
</style>
