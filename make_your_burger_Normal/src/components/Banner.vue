<template>
    <div id="main-banner">
        <h1>Make your <span>Burger</span></h1>
    </div>  
</template>

<script>
    export default {
        name: "Banner"
    }
</script>

<style scoped>
    #main-banner {
        background-image: url('../../public/img/burger.jpg');
        /* background-position: 0 -250px; */
        background-position: 0;
        background-size: cover;
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }
    #main-banner h1 {
        color: #fff;
        text-align: center;
        font-size: 60px;
        background-color: rgba(34, 34, 34, 0.521);
        padding: 20px 40px;
    }
    #main-banner h1 span {
        color: #fcba03;
    }
</style>