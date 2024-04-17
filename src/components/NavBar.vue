<template>
  <v-app-bar app color="primary" dark>
    <v-spacer></v-spacer>
    <v-btn to="/inicio" text color="white">Inicio</v-btn>
    <v-btn to="/sobre" text color="white">Sobre Mim</v-btn>
    <v-btn to="/experiencias" text color="white">Experiências</v-btn>
    <v-btn to="/projetos" text color="white">Projetos</v-btn>
    <v-btn to="/servicos" text color="white">Serviços</v-btn>
    <v-btn to="/contato" text color="white">Contato</v-btn>
    <v-spacer></v-spacer>
  </v-app-bar>
</template>

<script setup lang="ts">
  // Importações necessárias para o roteamento
  import { useRouter } from 'vue-router'
  const router = useRouter()
</script>