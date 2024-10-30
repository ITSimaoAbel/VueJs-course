<!-- SCRIPT -->
<script setup>

    //Importar componente 
    import Exemplo11Props2 from './Exemplo11Props2.vue';

    //variaveis
    let cidade = 'Maputo';
    let cidades = ['Matola', 'Maputo', 'Chimoio', 'Xai-Xai'];

    //funcao
    function mensagem() {
        alert('Funcao criada no componente: Exemplo11Props1');
    }
</script>

<!-- HTML -->
 <template>
    <Exemplo11Props2 nome="Simao" idade="25" :cidade="cidade" :vetor="cidades" :funcao="mensagem"></Exemplo11Props2>
 </template>