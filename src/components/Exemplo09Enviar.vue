<!-- SCRIPT -->
<script setup>

    //Funcao para validar formulario
    function validarFormulario(event){
        alert("formulário enviado com sucesso!");

        event.preventDefault();
    }

</script>

<!-- HTML -->
 <template>
    <form action="http://www.ralflima.com" @submit="validarFormulario">
        <input type="submit" value="Enviar formulario">
    </form>
 </template>