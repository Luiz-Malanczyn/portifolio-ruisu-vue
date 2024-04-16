<template>
  <div class="home">
    <h5>Olá, seja bem vindo!</h5>
    <h1>Eu sou Luiz</h1>
    <p class="">
      |
      <span>Cientista de Dados</span>
      |
      <span>Analista de BI</span>
      |
      <span>Full Stack Developer</span>
      |
    </p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

export default defineComponent({
  name: 'HomeView',
});
</script>
