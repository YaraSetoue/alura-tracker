<template>
    <div class="box">
        <div class="columns">
            <div class="column is-8" role="form" ariar-label="Formulario para criação de uma nova tarefa">
                <input type="text" class="input" placeholder="Qual tarefa você deseja iniciar?">
            </div>
            <div class="column">
                <Temporizador />
            </div>
        </div>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from "vue";
    import Temporizador from './Temporizador.vue';

    export default defineComponent({
        name: 'FormularioComponent',
        components: {
            Temporizador
        }
    });
</script>