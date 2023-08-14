<template>
  <div>Hello {{ value }}</div>

  <div>
    <p>Primeiro parágrafo do texto.</p>
    <p>Segundo parágrafo do texto.</p>
    <p>Terceiro parágrafo do texto.</p>
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
