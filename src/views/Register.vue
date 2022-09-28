<template>
<div class="register"></div>
    <section class="main">
        <div class="card-blue">
            <img src="../assets/Login.png" alt="">
            <div class="text-action">
                <div class="title-login">
                    <h2>Bem-Vindo de volta</h2>
                    <p>Acesse sua conta agora!</p>
                </div>
                <div class="entry-button">
                    <a href="#" >Entrar</a>
                </div>
                <a class="not-password" href="#">Esqueci minha senha</a>
            </div>
        </div>
        <div class="form-card">
            <div class="title-form">
                <h2>Crie sua conta</h2>
                <span>Preencha seus dados</span>
            </div>

            <form action="#">
                <label for="name"></label>
                <input type="text">
            </form>
        </div>
    </section>
</template>

<script>
    export default {
        name: 'Register'
    }
</script>

<style scoped>

    @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
    
    :root {
        --text-shadow: 0rem .25rem .25rem rgba(0, 0, 0, 0.25);
    }
    
    * {
        margin: 0;
        padding: 0;
        font-family: 'Poppins', sans-serif;
        text-decoration: none;
        list-style: none;
    }
    
    .main{
        display: flex;
    }
    
    .card-blue {
        background: #3C60A6;
        max-width: 17.5rem;
        display: flex;
        align-items: center;
        flex-direction: column;
        text-align: center;
        padding: 1.25rem;
        height: 100vh;
    }
    
    .title-login {
        margin-bottom: 2.1875rem;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    
    .card-blue h2 {
        font-size: 1.5rem;
        font-weight: 900;
        max-width: 10rem;
        color: #44D794;
        text-shadow: 0rem .25rem .25rem rgba(0, 0, 0, 0.25);;
        margin-bottom: 2.125rem;
        display: flex;
    }
    
    .card-blue p {
        font-size: .875rem;
        font-weight: 500;
        color: #FFF;
        text-shadow: 0rem .25rem .25rem rgba(0, 0, 0, 0.25);;
    }
    
    .entry-button {
        margin-bottom: 2rem;
    }
    
    .entry-button a {
        color: #44D794;
        border: .1875rem solid #44D794;
        box-shadow: 0rem .25rem .25rem rgba(0, 0, 0, 0.25);
        border-radius: 1.25rem;
        padding: 1rem 4rem;
        font-weight: 900;
    }
    
    .not-password {
        color: #FFF;
        font-size: 10pt;
    }
    
    .form-card {
        justify-content: center;
        align-items: center;
        width: 100vw;
    }
    </style>