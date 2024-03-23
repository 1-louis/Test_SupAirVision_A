<template>
    <div>
      <input v-model="message" placeholder="Écrivez un message pour l'enfant" />
      <HelloWorld :message="message" />
      <p>hello</p>
    </div>
  </template>
  
  <script setup>
  import { ref } from 'vue';
  import HelloWorld from '../components/HelloWorld.vue';
  
  // Création d'une référence réactive pour le message
  const message = ref('');
  </script>
  