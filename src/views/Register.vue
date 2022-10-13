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
            </div>
        </div>
        <div class="form-card">
            <div class="title-form">
                <h2 class="title">Crie sua conta</h2>
                <span>Preencha seus dados</span>
            </div>

            <form action="#">
                    
                <span class="ipt">
                    <img src="../assets/person-outline.svg" alt="" >
                    <input type="text" placeholder="Nome">
                </span>
                <br>
               
                <span class="ipt">
                    <img src="../assets/mail-outline.svg" alt="" >
                    <input type="text" placeholder="E-mail">
                </span><br>
              
                <span class="ipt">
                    <img src="../assets/lock-closed-outline.svg" alt="" >
                    <input type="password" placeholder="Senha">
                </span><br>

                <input type="submit" class="btn" value="Cadastrar">
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
        max-width: 20rem;
        display: flex;
        align-items: center;
        flex-direction: column;
        text-align: center;
        height: 120vh;
        padding: 25px;
        
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
        color: #FFF;
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
        color: #FFF;
        border: .1875rem solid #343C54;
        background: #6464AC;
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

    .ipt {
        margin-top: 5%;
        width: 50%;
        height: 47px;
        border-radius: .625rem;
        background-color: #E3E3E3;
        border: #E3E3E3;
        padding-left: .625rem ;
        display: flex;
        margin: 0 auto;
        margin-top: 1rem;
    }

    .ipt img {
        width: 1.5625rem;
    }

    .ipt input {
        background: none;
        border: none;
        padding-left: 2.5rem;
        width: 100%;
        margin-left: -2.1875rem;
        border-radius: .625rem;
    }

    .ipt input:focus {
        outline: none;
    }

    .title {
        margin-bottom: 3%;
    }

    .title-form {
        color: #3C60A6;
        text-shadow: 3px 8px 5px #E3E3E3;
        margin-top: 5%;
    }

    .btn{
        margin-top: 5%;
        min-width: 25%;
        height: 60px;
        background-color: #6464AC;
        color: #FFF;
        border-radius: 20px;
        font-weight: bold;
        font-size: 20px;
        cursor: pointer;
    }
</style>

