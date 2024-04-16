<template>
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="#">
          Navbar
        </a>
      </div>
      <div class="navbar-menu">
        <div class="navbar-start">
          <a v-for="(button, index) in buttons" :key="index" class="navbar-item" @click="handleButtonClick(button)">
            {{ button }}
          </a>
        </div>
      </div>
    </nav>
  </template>
  
  <script lang="ts">
  import { Vue, Component } from 'vue-property-decorator';
  
  @Component
  export default class NavBar extends Vue {
    buttons: string[] = ['Button 1', 'Button 2', 'Button 3', 'Button 4', 'Button 5', 'Button 6'];
  
    handleButtonClick(buttonName: string): void {
      // Aqui você pode adicionar a lógica para manipular o clique do botão
      console.log(`Botão clicado: ${buttonName}`);
    }
  }
  </script>
  
  <!-- Você pode manter o mesmo estilo, ou ajustar conforme necessário -->
  <style scoped>
  /* Adicione o link para o arquivo Bulma CSS */
  @import "~bulma/css/bulma.css";
  
  /* Estilos adicionais específicos para o componente NavBar, se necessário */
  </style>
  