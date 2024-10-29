<!-- SCRIPT -->
 <script setup> 
    // Variavel
    let texto = '<p style="color:red">A prendendo a directiva v-html</p>';

</script>

<!-- SCRIPT -->
 <template>
    <div v-html="texto"></div>

    <div>{{ texto }}</div>
 </template>