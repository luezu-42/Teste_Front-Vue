<template>
  <div class="fix">
    <div class="details">
      <div class="details__title">
        <router-link to="/">
          <img
            src="../../assets/images__details/orange__arrow.svg"
            alt="Back Arrow"
          />
        </router-link>
        <div class="details__title menssage">{{ title }}</div>
      </div>
      <carousel
        :navigation-enabled="true"
        :per-page="2"
        :per-page-custom="[[1000, 2]]"
      >
        <slide>
          <div class="details__slide">
            <img
              src="../../assets/images__details/prev__image.svg"
              alt="Preview"
              class="details__slide__img"
            />
            <div class="details__slide__text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiu smod tempor incididunt ut labore et dolore magna aliqua.
            </div>
          </div>
        </slide>
        <slide>
          <div class="details__slide">
            <img
              src="../../assets/images__details/prev__image.svg"
              alt="Preview"
              class="details__slide__img"
            />
            <div class="details__slide__text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiu smod tempor incididunt ut labore et dolore magna aliqua.
            </div>
          </div>
        </slide>

        <slide>
          <div class="details__slide">
            <img
              src="../../assets/images__details/prev__image.svg"
              alt="Preview"
              class="details__slide__img"
            />
            <div class="details__slide__text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiu smod tempor incididunt ut labore et dolore magna aliqua.
            </div>
          </div>
        </slide>
      </carousel>
      <div class="details__text">
        O aplicativo Histórico Empresarial permite ao usuário ter acesso a todos
        os fatos e acontecimentos relevantes de uma empresa desde o seu ano de
        fundação. Tenha acesso aos principais eventos corporativos de uma
        empresa, como: marcos jurídicos, mudança no quadro societário, aumento
        de capital,reportagens e muito mais.
        <br /><br />
        Após realizar a consulta, o histórico é salvo automaticamente, tornando
        as informações acessíveis ao usuário. A linha do tempo pode também ser
        exportada no formato PDF.
      </div>
      <div class="banner__value">
        <div class="value">
          R$
        </div>
        <div class="value__title">
          40,00
        </div>
        <router-link to="/" class="button__details">
          Habilitar
        </router-link>
      </div>
    </div>
  </div>
</template>

<script>
import { Carousel, Slide } from "vue-carousel";

export default {
  name: "Details-container",
  props: {
    title: String,
  },
  components: {
    Carousel,
    Slide,
  },
};
</script>

<style src="./style.scss" lang="scss" scoped />
