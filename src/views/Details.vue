<template>
<div>
  <DetailsContainer :title="$route.params.n"></DetailsContainer>
  </div>
</template>

<script>
import DetailsContainer from "../components/Details/Details__container";

export default {
    name: "Details",
    components: {
        DetailsContainer,
    }
}
</script>

<style>

</style>