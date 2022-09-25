<template>
<div class="welcome">
    <h1>Tela Welcome</h1>
<nav>
    <router-link to="/register">Cadastre-se</router-link>
  </nav>
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
