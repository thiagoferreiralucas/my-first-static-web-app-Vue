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

  <h3>Tabela<h3>
      
    <table border=1px>
    <caption>Produtos</caption>
    <thead>
        <tr>
            <th>Produto</th>
            <th>Preço</th>
            <th>Quantidade</th>
            <th>Total</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>iPad</th>
            <td>3289,00</th>
            <td>5</th>
            <td>16445,00</th>
        </tr>
        <tr>
            <td>Sansung S9</th>
            <td>2649,00</th>
            <td>8</th>
            <td>21192,00</th>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td colspan="3">Total</td>
            <td>37637,00</td>
        </tr>
    </tfoot>
</table>
    
  </div>
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
