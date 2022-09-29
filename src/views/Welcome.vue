<template>
<div class="welcome">
    <section class="main">
        <div class="card-blue">
            <h1>PROVOCARE</h1>
        </div>
    </section>
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
