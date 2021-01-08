<template>
  <div class="Bar">
    <Box
      title="Todos"
      alt="Todos"
      icon="todos__icon.svg"
      className="Box active"
    />
    <Box
      title="Prossional"
      alt="Professional"
      icon="profissional__icon.svg"
      className="Box"
    />
    <Box
      title="Reguladores"
      alt="Reguladores"
      icon="reguladores__icon.svg"
      className="Box"
    />
    <Box
      title="Sócio Ambiental"
      alt="Sócio Ambiental"
      icon="ambiente__icon.svg"
      className="Box"
    />
    <Box
      title="Júridico"
      alt="Júridico"
      icon="juridico__icon.svg"
      className="Box"
    />
    <Box
      title="Listas Restritivas"
      alt="Listas Restritivas"
      icon="listas__icon.svg"
      className="Box"
    />
    <Box
      title="Mídias / Internet"
      alt="Mídias e Internet"
      icon="midia__icon.svg"
      className="Box"
    />
    <Box
      title="Bens e Imóveis"
      alt="Bens e Imóveis"
      icon="bens__icon.svg"
      className="Box"
    />
    <Box
      title="Cadastro"
      alt="Cadastro"
      icon="cadastro__icon.svg"
      className="Box"
    />
    <Box
      title="Financeiro"
      alt="Financeiro"
      icon="financeiro__icon.svg"
      className="Box"
    />
  </div>
</template>

<script>
import Box from "./BoxSelect";

export default {
  name: "Bar",
  components: {
    Box,
  },
};
</script>

<style src="./style.scss" lang="scss" scoped />
