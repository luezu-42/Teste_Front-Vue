<template>
  <div>
    <Bar />
    <Select />
    <CardList />
  </div>
</template>

<script>
import Bar from "../components/GreyBar/Bar";
import Select from "../components/Select/Select";
import CardList from "../components/Cards/Card__List";

export default {
  name: "Home",
  components: {
    Bar,
    Select,
    CardList,
  },
};
</script>
