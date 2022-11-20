<template>
    <main class="main">
          <!-- <div class="container">
            <button class="btn-card">Home</button>
            <button class="btn-card">Desafios</button>
            <button class="btn-card">Respostas</button>
            <button class="btn-card">Seus Desafios</button>
        </div> -->
        <div class="wrapper">
            <div class="input-box">
                <div class="post-card">
                    <input type="text" class="input" placeholder="Digite algo...">
                    <input type="submit" class="btn" value="Postar">
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
        color: #fff;
    }

    h1 {
        color: #000;
    }

    main {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .wrapper {
        background: #212121;
        box-shadow: 6px 4px 5px rgba(0, 0, 0, 0.25);
        border-radius: 20px;
        width: 40%;
        border-radius: 15px;
        padding: 25px 25px 15px 25px;
        margin-top: 2%;
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
        background: #1DA1F2;
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

    /* .container{
        display: flex;
        justify-content: space-around;
        width: 20%;
        height: 40%;
        background-color: #3c60a6;
    }

    .btn-card{
        background-color: #3c60a6;
    } */
</style>
