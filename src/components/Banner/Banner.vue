<template>
<div>
  <carousel
    :per-page="1"
    :per-page-custom="[
      [1000, 1],
      [1000, 1],
    ]"
    v-bind:autoplay="true"
    v-bind:loop="true"
  class="carousel__desktop" >
    <slide>
      <img
        src="../../assets/images_banner/DarkBanner.svg"
        alt="Dark Banner"
        class="banner"
      />
      <div class="banner__container__dark">
        <div class="banner__container__title">
          <img src="../../assets/images_banner/WhiteLogo.svg" alt="Logo" />
          <div class="line"></div>
          Historico Empresarial
        </div>
        <div class="banner__container__text">
          O aplicativo Histórico Empresarial permite ao usuário ter acesso a
          todos <br />
          os fatos e acontecimentos relevantes de uma empresa desde o seu ano
          <br />
          de fundação.
        </div>
        <div class="banner__value">
          <div class="value">
            R$
          </div>
          <div class="banner__container__title">
            40,00
          </div>
          <router-link :to="{name:'details' , params: {n:'Histórico Empresarial'}}" class="button__details">
            Saiba mais
          </router-link>
        </div>
      </div>
    </slide>

    <slide>
      <img
        src="../../assets/images_banner/WhiteBanner.svg"
        alt="White Banner"
        class="banner"
      />
      <div class="banner__container__light">
        <div class="banner__container__title">
          <img src="../../assets/images_banner/DarkLogo.svg" alt="Logo" />
          <div class="line"></div>
          Historico Empresarial
        </div>
        <div class="banner__container__text">
          O aplicativo Histórico Empresarial permite ao usuário ter acesso a
          todos <br />
          os fatos e acontecimentos relevantes de uma empresa desde o seu ano
          <br />
          de fundação.
        </div>
        <div class="banner__value">
          <div class="value">
            R$
          </div>
          <div class="banner__container__title">
            40,00
          </div>
          <router-link :to="{name:'details' , params: {n:'Histórico Empresarial'}}" class="button__details">
            Saiba mais
          </router-link>
        </div>
      </div>
    </slide>
  </carousel>

  <carousel
    :per-page="1"
    :per-page-custom="[
      [1000, 1],
      [1000, 1],
    ]"
    v-bind:autoplay="true"
    v-bind:loop="true"
  class="carousel__mobile" >
    <slide class="slide">
      <img
        src="../../assets/images_banner/mobileDark.svg"
        alt="Dark Banner"
        class="banner"
      />
      <div class="banner__container__dark">
        <div class="banner__container__title">
          <img src="../../assets/images_banner/WhiteLogo.svg" alt="Logo" class="banner__logo" />
          <div class="line"></div>
          Historico Empresarial
        </div>
        <div class="banner__container__text">
          O aplicativo Histórico Empresarial permite ao usuário ter acesso a
          todos <br />
          os fatos e acontecimentos relevantes de uma empresa desde o seu ano
          <br />
          de fundação.
        </div>
        <div class="banner__value">
          <div class="value">
            R$
          </div>
          <div class="banner__container__title">
            40,00
          </div>
          <router-link :to="{name:'details' , params: {n:'Histórico Empresarial'}}" class="button__details">
            Saiba mais
          </router-link>
        </div>
      </div>
    </slide>

    <slide>
      <img
        src="../../assets/images_banner/mobileWhite.svg"
        alt="White Banner"
        class="banner"
      />
      <div class="banner__container__light">
        <div class="banner__container__title">
          <img src="../../assets/images_banner/DarkLogo.svg" alt="Logo" class="banner__logo" />
          <div class="line"></div>
          Historico Empresarial
        </div>
        <div class="banner__container__text">
          O aplicativo Histórico Empresarial permite ao usuário ter acesso a
          todos <br />
          os fatos e acontecimentos relevantes de uma empresa desde o seu ano
          <br />
          de fundação.
        </div>
        <div class="banner__value">
          <div class="value">
            R$
          </div>
          <div class="banner__container__title">
            40,00
          </div>
          <router-link :to="{name:'details' , params: {n:'Histórico Empresarial'}}" class="button__details">
            Saiba mais
          </router-link>
        </div>
      </div>
    </slide>
  </carousel>

  <carousel
    :per-page="1"
    :per-page-custom="[
      [1000, 1],
      [1000, 1],
    ]"
    v-bind:autoplay="true"
    v-bind:loop="true"
  class="carousel__mobile__smarphone" >
    <slide class="slide">
      <img
        src="../../assets/images_banner/smartphoneDark.svg"
        alt="Dark Banner"
        class="banner"
      />
      <div class="banner__container__dark">
        <div class="banner__container__title">
          <img src="../../assets/images_banner/WhiteLogo.svg" alt="Logo" class="banner__logo" />
          <div class="line"></div>
          Historico Empresarial
        </div>
        <div class="banner__container__text">
          O aplicativo Histórico Empresarial permite ao usuário ter acesso a
          todos <br />
          os fatos e acontecimentos relevantes de uma empresa desde o seu ano
          <br />
          de fundação.
        </div>
        <div class="banner__value">
          <div class="value">
            R$
          </div>
          <div class="banner__container__title">
            40,00
          </div>
          <router-link :to="{name:'details' , params: {n:'Histórico Empresarial'}}" class="button__details">
            Saiba mais
          </router-link>
        </div>
      </div>
    </slide>

    <slide>
      <img
        src="../../assets/images_banner/smartphoneWhite.svg"
        alt="White Banner"
        class="banner"
      />
      <div class="banner__container__light">
        <div class="banner__container__title">
          <img src="../../assets/images_banner/DarkLogo.svg" alt="Logo" class="banner__logo" />
          <div class="line"></div>
          Historico Empresarial
        </div>
        <div class="banner__container__text">
          O aplicativo Histórico Empresarial permite ao usuário ter acesso a
          todos <br />
          os fatos e acontecimentos relevantes de uma empresa desde o seu ano
          <br />
          de fundação.
        </div>
        <div class="banner__value">
          <div class="value">
            R$
          </div>
          <div class="banner__container__title">
            40,00
          </div>
          <router-link :to="{name:'details' , params: {n:'Histórico Empresarial'}}" class="button__details">
            Saiba mais
          </router-link>
        </div>
      </div>
    </slide>
  </carousel>
  </div>
</template>
<script>
import { Carousel, Slide } from "vue-carousel";

export default {
  components: {
    Carousel,
    Slide,
  },
};
</script>
<style src="./style.scss" lang="scss" scoped />
