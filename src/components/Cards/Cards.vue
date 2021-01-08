<template>
  <div class="card">
      <div class="card__content">
          <div class="card__content__space">
          <img :src="require(`@/assets/card__icon/${iconCard}`)" :alt="altCard">
          <div class="card__content__title">{{ titleCard }}</div>
          <div class="card__content__text">{{ textCard }}</div>
          </div>
      </div>

      <div class="card__props">
          <div> {{ valueCard }} </div>
          <router-link :to="{name:'details' , params: {n:titleCard}}" class="card__content__link"> {{ linkCard }} </router-link>
      </div>
  </div>
</template>

<script>
export default {
    name: "Cards",
    props: {
        iconCard: String,
        altCard: String,
        titleCard: String,
        valueCard: String,
        linkCard: String,
        textCard: String
    }
}
</script>

<style src="./style.scss" lang="scss" scoped/>