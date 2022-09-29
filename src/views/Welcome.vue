<template>
<div class="welcome">
    <section class="main">
        <div class="card-blue">
            <div class="text-action">
                <div class="title">
                    <h1>
                        <font color="#44D794">&lt;</font>
                        PROVOCARE
                        <font color="#44D794">&gt;</font>
                    </h1>
                </div>
                <div class="container">
                    <div class="about">
                        <a href="#" >Quem Somos</a>
                    </div>
                    <div class="contact">
                        <a href="#" >Contato</a>
                    </div>
                </div>
            </div>
        </div>
        <div class="logon-card">
            <div class="title-logon">
                <h2>
                    Junte-se a comunidade desenvolvedora mais estimulante
                     e alcance seus objetivos se divertindo e contribuindo no <br>
                    <font color="#44D794">&lt;</font>
                    PROVOCARE
                    <font color="#44D794">&gt;</font>
                </h2>
                <div class="container-2">
                    <nav class="login">
                        <router-link to="/register" class="router-login">Entrar</router-link>
                    </nav>
                    <nav class="register">
                        <router-link to="/register" class="router-register">Cadastre-se</router-link>
                    </nav>
                </div>
            </div>
        </div>
    </section>
</div>
</template>

<script>
    import Register from './Register.vue'

    export default{
        name: 'Welcome',
        components: {
            Register
        }
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
        align-items: flex-start;
        flex-direction: row;
        text-align: center;
        padding: 10rem;
        height: 100vh;
    }

    .title {
        width: 589px;
        height: 86px;
        margin-bottom: 2.1875rem;
        display: flex;
        flex-direction: row;
        align-items: flex-start;
    }

    .card-blue h1 {
        font-size: 3rem;
        font-weight: 900;
        line-height: 4.375rem;
        letter-spacing: 0.07em;
        max-width: 10rem;
        color: #fff;
        text-shadow: 0rem .25rem .25rem rgba(0, 0, 0, 0.25);;
        margin-bottom: 2.125rem;
        display: flex;
        font-weight: 700;
    }

    .container {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        width: 380px;
        margin-left: auto;
        margin-right: auto;
    }

    .about, .contact {
        margin-bottom: 3rem;
    }
    
    .about a {
        color: #44D794;
        border: .1875rem solid #44D794;
        box-shadow: 0rem .25rem .25rem rgba(0, 0, 0, 0.25);
        border-radius: 1.25rem;
        padding: 1rem 4rem;
        font-weight: 900;
    }

    .contact a {
        color: #44D794;
        border: .1875rem solid #44D794;
        box-shadow: 0rem .25rem .25rem rgba(0, 0, 0, 0.25);
        border-radius: 1.25rem;
        padding: 1rem 4rem;
        font-weight: 900;
    }
    
    .logon-card {
        background: linear-gradient(180deg, rgba(68, 215, 148, 0.99) 0%, rgba(68, 215, 148, 0.804375)
            38.02%, rgba(0, 59, 210, 0.5049) 100%);
        max-width: 17.5rem;
        display: flex;
        align-items: flex-start;
        flex-direction: row;
        text-align: center;
        padding: 10rem;
        height: 100vh;
    }

    .logon-card h2 {
        background: linear-gradient(180deg, rgba(68, 215, 148, 0.99) 0%,
            rgba(68, 215, 148, 0.804375) 38.02%, rgba(0, 59, 210, 0.5049) 100%);
        box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
        border-radius: 16px;
    }

    .container-2 {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        width: 380px;
        margin-left: auto;
        margin-right: auto;
    }

    .login {
        background: #274F9E;
        border: 3px solid #44D794;
        box-shadow: 4px 4px 4px rgba(0, 0, 0, 0.25);
        border-radius: 20px;
        padding: 1rem 4rem;
        font-weight: 900;
    }
    
    .router-login {
        color: #fff;
    }

    .register {
        color: #fff;
        background: #274F9E;
        border: 3px solid #44D794;
        box-shadow: 4px 4px 4px rgba(0, 0, 0, 0.25);
        border-radius: 20px;
        padding: 1rem 4rem;
        font-weight: 900;
    }

    .router-register {
        color: #fff;
    }
    
</style>