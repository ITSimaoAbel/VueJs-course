<!--SCRIPT-->
<script setup>
    //Vetor
    let nomes = ['Alice', 'Joao', 'Maria', 'Jose', 'Pedro'];
</script>

<!-- HTML -->
<template>
    <ul>
        <li v-for="nome in nomes">{{ nome }}</li>
    </ul>
</template>