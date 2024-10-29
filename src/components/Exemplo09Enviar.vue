<!-- SCRIPT -->
<script setup>

    //Funcao para validar formulario
    function validarFormulario(){
        alert("formulário enviado com sucesso!");
    }

</script>

<!-- HTML -->
 <template>
    <form @submit="validarFormulario">
        <input type="submit" value="Enviar formulario">
    </form>
 </template>