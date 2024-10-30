<!-- SCRIPT -->
<script setup>
    // importacoes
    import { onMounted, ref } from 'vue';

    // variaveis
    let texto = ref('Hello World');

    //Lifecycle onMounted
    onMounted(() =>{
        setTimeout(() => {
            texto.value = 'Alterando texto!';
        }, 3000);
    });
</script>


<!-- HTML -->
<template>
    <h1>{{ texto }}</h1>
</template>
