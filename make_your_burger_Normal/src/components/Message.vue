<template>
    <div class="message-container">
        <!-- <p>Esta é uma mensagem do sistema</p> -->
        <p>{{msg}}</p>
    </div>
</template>

<script>
export default {
    name: "Message",
    props: {
        msg: String
    }
}
</script>

<style scoped>
    .message-container {
        color: #004085;
        background-color: #cce5ff;
        border: 2px solid #b8daff;
        border-radius: 5px;
        padding: 10px;
        max-width: 375px;
        margin: 30px auto;
    }
</style>