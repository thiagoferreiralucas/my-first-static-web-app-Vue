<template>
  <div>
    <h1>Bem-Vindo a página do {{ value }}, espero que tenha gostado!</h1>
    <p>teste</p>

    <h2>Principais termos do glossário de Cloud Computing</h2>

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

    <tr>

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
