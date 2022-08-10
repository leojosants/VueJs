<!--  -->
<template>
    <div>
        <h1>Olá, Vue</h1>
        
        <p>
            Meu nome é {{ nome }} e sou {{ profissao }}!
            <Reutilizacao />
        </p>

        <MultiplosEventos />
        <Reutilizacao />
        <Reutilizacao />
        <Reutilizacao />
    </div>
</template>

<script>
    import MultiplosEventos from './MultiplosEventos.vue';
    import Reutilizacao from './Reutilizacao.vue';

    export default {
        name: 'PrimeiroComponente',
        
        components: {
            MultiplosEventos,
            Reutilizacao
        },

        data() {
            return {
                nome: "Leonardo",
                profissao: "Programador"
            }
        }
    }
</script>