<script setup>
    const year = new Date().getFullYear();
</script>

<template>
    <footer class="footer">
        <div>
            <img src="./../assets/logo_bg.svg" class="logo" alt="БАРС Груп" />
        </div>
        <div>(c) {{ year }} БАРС Груп</div>
    </footer>
</template>

<style scoped>
    .footer {
        margin-top: 70px;
        text-align: center;
        color: #888;
    }
    .logo {
        height: 6em;
        padding: 1.5em;
        will-change: filter;
        transition: filter 300ms;
    }
    .logo:hover {
        filter: drop-shadow(0 0 2em #646cffaa);
    }
</style>
