<!-- SCRIPT -->
<script setup>
    //Funcao de mensagem
    function mensagem() {
        alert("Executando a funcao mensagem");
    }
</script>


<!-- HTML -->
 <template>
    <input type="text" @keyup.enter="mensagem">
 </template>