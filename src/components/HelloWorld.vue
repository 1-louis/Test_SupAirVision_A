<template>
  <div>Message du parent : {{ message }}</div>
</template>

<script setup>
// Importation de defineProps pour définir les props attendues par le composant
const props = defineProps({
  message: String,
});
</script>
