<script>

export default {
    name: 'MeuComponente',
    props: {
        titulo: {
            
            type: String,
            required: true
        },
        conteudo: {

            type: String,
            required: true
            
        }
    }
}
</script>

<template>
    <div>
        <h1>{{ titulo }}</h1>
        <p>{{ conteudo }}</p>
    </div>

</template>

<style>

</style>