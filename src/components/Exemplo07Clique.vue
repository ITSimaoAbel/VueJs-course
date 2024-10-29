<!-- SCRIPT -->
 <script setup>

    //>Funcao
    function mensagem() {
        alert('Trabalhando com eventos de clique');
    }

</script>


<!-- HTML -->
 <template>

   <!-- <h1>Trabalhando com eventos de clique</h1> -->
    <button @click="mensagem()">Clique aqui</button>

 </template>
