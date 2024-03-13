<script setup>
    const items = ['São Paulo', 'Rio de Janeiro', 'Belo Horizonte', 'Salvador', 'Fortaleza', 'Curitiba', 'Manaus', 'Recife', 'Porto Alegre', 'Brasília',].sort()
</script>
<template>
  <h1>Lista de cidades ordenadas em ordem alfabética:</h1>
  <ul>
    <li v-for="(item, index) in items" :key="index"> {{ item }} </li>
  </ul>
</template>