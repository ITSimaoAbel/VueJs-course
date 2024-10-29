<!-- SCRIPT -->
<script setup>

  //variaveis
  let nome = 'Simao';
  let idade = 25;
  let nr1 = 10  
  let nr2 = 20;

</script>

<!-- HTML -->
 <template>
  <p>{{'Ola ' +  nome + ' voce tem ' + idade + ' anos.' }}</p>
  <p>O valor de nr1 + nr2 é: {{ nr1 + nr2 }}</p>
 </template>