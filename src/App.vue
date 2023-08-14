<template>
  <div>
    <h1>Bem-Vindo a página do {{ value }}, espero que tenha gostado!</h1>
    <p>teste</p>

    <h2>Tags de Texto</h2>

      <h3>Principais termos do glossário de Cloud Computing</h3>
  
      <!-- Texto padrão -->
      <p>Texto qualquer</p>
          
      <!-- Negrito e Itálico -->
      <p>Texto em <b>Negrito</b> e <i>Itálico</i></p>
      
      <!-- Sobrescrito e Subescrito -->
      <p>2<sup>2</sup> = 4 e H<sub>2</sub>O = Água!</p>

    <hr>

      <h3>Principais termos do glossário de Cloud Computing</h3>

      <dl>
          <dt>Baas</dt>
          <dd>Backend as a Service</dd>
          <dt>Iaas</dt>
          <dd>Infrastructure as a Service</dd>
          <dt>Paas</dt>
          <dd>Platform as a Service</dd>
          <dt>Saas</dt>
          <dd>Software as a Service</dd>
      </dl>

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
