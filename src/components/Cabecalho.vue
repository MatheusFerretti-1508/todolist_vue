<script setup> 
    const props = defineProps(['TarefasPendentes'])
</script>

<template>
    <header class="p-5 mb-4 mt-4 bg-light rounded-3">
        <h1>Minhas tarefas</h1>
        <p>
            Você possui {{ props.TarefasPendentes }} tarefas pendentes
        </p>
    </header>
</template>

<script>
    export default {
        name: "Cabecalho",
    }
</script>