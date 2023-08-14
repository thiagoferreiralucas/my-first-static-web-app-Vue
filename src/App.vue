<template>
  <div>
    <h1>Bem-Vindo a página do {{ value }}, espero que tenha gostado!</h1>
    <p>teste</p>
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
