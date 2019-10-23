<template lang="html">
  <div v-if="country">
    <h1>Country Detail</h1>
    <h3>{{country.name}}</h3>
    <p>{{country.population}}</p>
  </div>
</template>

<script>
export default {
  name: "country-detail",
  props: ["country"]
};
</script>

<style lang="css" scoped>
</style>
