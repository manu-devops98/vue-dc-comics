<template>
  <div class="card">
    <div class="container-img">
      <img :src="img" :alt="alt" />
    </div>
    <h2>{{ titolo }}</h2>
  </div>
</template>

<script>
export default {
  name: "Cards",
  props: ["img", "alt", "titolo"],
};
</script>

<style lang="scss">
.card {
  width: 150px;
  margin: 10px;
  cursor: pointer;
  .container-img {
    height: 150px;
    width: 150px;
    overflow: hidden;
    img {
      width: 100%;
    }
  }
  h2 {
    font-size: 0.8em;
    text-transform: uppercase;
    margin-top: 10px;
  }
  &:hover {
    transform: scale(1.1);
  }
}
</style>
