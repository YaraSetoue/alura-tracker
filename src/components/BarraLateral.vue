<template>
    <header>
        <h1>
            <img src="../assets/logo.png" alt="Logo">
        </h1>
    </header>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'BarraLateral'
    })
</script>

<style scoped>
    header {
        padding: 1rem;
        background: #0d3b66;
        width: 100%;
        height: 100vh;
    }
    header h1 {
        width: 100%;
        text-align: center;
        height: 100px;
    }
    header h1 img{
        height: 100%;
    }
    @media only screen and (max-width: 768px) {
        header {
            padding: 2.5rem;
            height: auto;
        }
    }
</style>