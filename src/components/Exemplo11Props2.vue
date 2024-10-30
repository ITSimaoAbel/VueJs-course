<!-- SCRIPT -->
 <script setup>

    //obter props
    const props = defineProps(['nome', 'idade']);
</script>

<!-- HTML -->
 <template>
    <h1>Nome: {{ nome }}</h1>
    <h1>Nome: {{ idade }}</h1>
 </template>