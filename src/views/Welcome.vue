<template>
<div class="welcome">
    <section class="main">
        <div class="card-blue">
            <div class="conic-gradient"></div>
            <div class="text-action">
                <div class="title">
                    <h1>
                        
                        <font color="#44D794">&lt;</font>
                        PROVOCARE
                        <font color="#44D794">&gt;</font> 
                    </h1>
                    
                </div>
                <div class="about">
                    <a href="#" >Quem Somos</a>
                </div>
                <div class="contact">
                  <a href="#" >Contato</a>
                </div>
                <img src="..\assets\Puzzle.png" alt="Puzzle" class="puzzle">
            </div>
        </div>
        <div class="logon-card">
            <div class="title-logon">
                <h2>
                    Junte-se a comunidade desenvolvedora mais estimulante
                     e alcance seus objetivos se divertindo e contribuindo no <br>
                    <font color="#fff">&lt;</font>
                    PROVOCARE
                    <font color="#fff">&gt;</font>
                </h2>
                <div class="container-2">
                    <nav class="login">
                        <router-link to="/login" class="router-login">Entrar</router-link>
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
        background: linear-gradient(180deg, rgba(68, 215, 148, 0.99) 0%, rgba(68, 215, 148, 0.804375)
            38.02%, rgba(0, 59, 210, 0.5049) 100%);
    }
    
    .card-blue {
        background: #3C60A6;
        max-width: 17.5rem;
        padding: 8rem;
        border: 1px solid #000000;
        box-shadow: 0px 4px 20px rgba(0, 0, 0, 0.25);
    }

    .conic-gradient {
        position: absolute;
        width: 600px;
        height: 370px;
        left: -57px;
        top: 400px;

        background: conic-gradient(from 236.56deg at 54.72% 27.17%, #00D1FF -106.88deg, #2400FF 157.5deg, #00D1FF 253.13deg, #2400FF 517.5deg);
        filter: blur(173.754px);
    }

    .title {
        
        width: 589px;
        height: 86px;
        margin-bottom: 2.1875rem;
    }

    .card-blue h1 {
        font-size: 3rem;
        font-weight: 700;
        line-height: 3rem;
        letter-spacing: 0.07em;
        max-width: 10rem;
        color: #fff;
        text-shadow: 0rem .25rem .25rem rgba(0, 0, 0, 0.25);;
        display: flex;
        
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

    .puzzle {
        display: flex;
        mix-blend-mode: hard-light;
        filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
        width: 300px;
        height: 300px;

    }
    
    .logon-card {
        flex-direction: row;
        text-align: center;
        padding: 10rem;
        height: 100vh;
        
    }

    .title-logon h2 {
        padding: 1rem;
        text-shadow: 0rem .25rem .25rem rgba(0, 0, 0, 0.25);;
    }

    .container-2 {
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
    .card-blue h1[data-v-e4731dd0] {
        justify-content: center;
        margin-left: 70px;
    }
</style>