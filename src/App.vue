<template>
  <div>
    Bem-Vindo a página do {{ value }}, espero que tenha gostado!
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
