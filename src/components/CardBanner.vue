<template>
  <v-card class="py-4 d-flex flex-column align-center justify-center text-center" color="surface-variant" rounded="lg" variant="outlined">
    <v-card-title class="ma-4">
      <h5 class="text-h5 font-weight-bold">Olá, seja bem vindo</h5>
      <h1 class="text-h1 font-weight-bold">Luiz</h1>
    </v-card-title>
    <v-card-text class="ma-4">
      <span>Cientista de dados | Analista de BI | Full Stack Developer</span>
    </v-card-text>
    <v-card class="py-4 mt-4 d-flex flex-row align-center justify-center text-center">
      <v-card-text class="ma-0">
        <h2>Sobre mim</h2>
      </v-card-text>
      <v-icon right>mdi-chevron-down</v-icon>
    </v-card>
    <v-card flat class="py-4 mt-4 d-flex flex-column align-center justify-center text-center">
      <v-row class="d-flex justify-space-around ma-4">
        <v-card-title class="ma-4 d-flex flex-column align-center">
          <span>LinkedIn</span>
          <v-btn icon>
            <v-icon>mdi-linkedin</v-icon>
          </v-btn>
        </v-card-title>
        <v-card-title class="ma-4 d-flex flex-column align-center">
          <span>GitHub</span>
          <v-btn icon>
            <v-icon>mdi-github</v-icon>
          </v-btn>
        </v-card-title>
        <v-card-title class="ma-4 d-flex flex-column align-center">
          <span>Email</span>
          <v-btn icon>
            <v-icon>mdi-email</v-icon>
          </v-btn>
        </v-card-title>
      </v-row>
    </v-card>
  </v-card>
</template>

<script setup lang="ts">
  // Importações necessárias para o roteamento
  import { useRouter } from 'vue-router'
  const router = useRouter()
</script>