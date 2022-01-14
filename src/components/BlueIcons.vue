<template>
  <div class="box">
    <img :src="img" :alt="alt" />
    <h3>{{ titolo }}</h3>
  </div>
</template>

<script>
export default {
  name: "BlueIcons",
  props: ["img", "alt", "titolo"],
};
</script>

<style lang="scss">
.box {
  display: flex;
  align-items: center;
  width: calc(100% / 5);
  margin-left: 3em;
  cursor: pointer;
  img {
    width: 20%;
  }
  h3 {
    font-size: 0.8em;
    margin-left: 1em;
    text-transform: uppercase;
  }
}
</style>
