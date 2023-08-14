<template>
  <div>

    <!-- Comentários -->
    <h1 id="#inicio">Bem-Vindo a página do {{ value }}, espero que tenha gostado!</h1>
    <p>teste</p>

    <hr>

    <h2>Tags para Parágrafo</h2>

      <!-- Quando menor o valor maior a importância -->
      <h1>Cabeçalho Principal</h1>
      <h2>Cabeçalho de Nível 2</h2>
      <h3>Cabeçalho de Nível 3</h3>
      <h4>Cabeçalho de Nível 4</h4>
      <h5>Cabeçalho de Nível 5</h5>
      <h6>Cabeçalho de Nível 6</h6>

    <hr>

    <h2>Tags para Texto</h2>
  
      <!-- Texto padrão -->
      <p>Texto qualquer</p>
          
      <!-- Negrito e Itálico -->
      <p>Texto em <b>Negrito</b> e <i>Itálico</i></p>
      
      <!-- Sobrescrito e Subescrito -->
      <p>2<sup>2</sup> = 4 e H<sub>2</sub>O = Água!</p>

    <hr>

    <h2>Listas</h2>
    
      <!-- Lista Ordenada ( ol - Order List | li - List Item ) -->
      <h3>Aprovados</h3>
      
      <ol>
          <li>Bia</li>
          <li>Pedro</li>
          <li>Ana</li>
          <li>João</li>
      </ol>
      
      <!-- Lista Desordenada ( ul - Unordered List ) -->
      <h3>Lista de Compras</h3>
      
      <ul>
          <li>Queijo</li>
          <li>Arroz</li>
          <li>Leite</li>
          <li>Pão</li>
      </ul>

    <hr>

    <h2>Novos links</h2>
    
    <a href="https://www.google.com.br" target="_black">Google</a>

    <a href="#inicio">Voltar para início</a>

    <hr>

    
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "Thiago"
    };
  }
};
</script>
