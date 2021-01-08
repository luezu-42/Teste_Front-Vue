<template>
  <div :class="className">
    <img
      :src="require(`@/assets/bar__icon/${icon}`)"
      :alt="alt"
      class="Box__icon"
    />
    <div class="Box__title">{{ title }}</div>
  </div>
</template>

<script>
export default {
  name: "Box",
  props: {
    title: String,
    icon: String,
    alt: String,
    className: String,
  },
};
</script>

<style src="./style.scss" lang="scss" scoped />
