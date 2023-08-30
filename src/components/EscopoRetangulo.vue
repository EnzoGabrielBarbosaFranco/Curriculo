<template>
  <div class="retangulo-vertical">
    <div class="circulo">
      <div class="imagem-curriculo">
        <img src="../imagens/imagemcurriculo.jpg" alt="Foto de Perfil">
      </div>
    </div>
    <div class="onda-cima">
      <img src="../imagens/onda-cima.jpeg" alt="Sua imagem">
    </div>
    <div class="onda-baixo">
      <img src="../imagens/onda-atualizada.jpeg" alt="Sua imagem">
    </div>
    <NomeEContato />
    <PerfilProfissional />
    <ExperienciaProfissional />
    <FormacaoAcademica />
    <HabilidadesEIdiomas />
  </div>
</template>

<script>
import NomeEContato from './NomeEContato.vue'
import PerfilProfissional from './PerfilProfissional.vue';
import ExperienciaProfissional from './ExperienciaProfissional.vue';
import FormacaoAcademica from './FormacaoAcademica.vue';
import HabilidadesEIdiomas from './HabilidadesEIdiomas.vue'

export default {
  components: {
    NomeEContato,
    PerfilProfissional,
    ExperienciaProfissional,
    FormacaoAcademica,
    HabilidadesEIdiomas,
  },
};
</script>

<style>
html {
  background-color: rgb(61, 61, 61);
}

.retangulo-vertical {
  width: 800px;
  height: 1100px;
  background-color: rgb(255, 255, 255);
  margin-left: auto;
  margin-right: auto;
  position: relative;
}

.circulo {
  width: 250px;
  height: 250px;
  background-color: rgb(255, 255, 255);
  border-radius: 50%;
  position: absolute;
  top: 10%;
  left: 10%;
  overflow: hidden;
}

.imagem-curriculo img {
  max-width: 100%;
  max-height: 100%;
}

.onda-cima,
.onda-baixo {
  position: absolute;
  left: 0;
  right: 0;
  height: 100px;
}

.onda-cima img,
.onda-baixo img {
  width: 100%;
  height: 100%;
}

.onda-cima {
  top: 0;
}

.onda-baixo {
  bottom: 0;
}
</style>