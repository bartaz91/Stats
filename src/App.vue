<template>
  <div class="app">
    <Tile v-for="tile in tiles" :name="tile" :key="tile" />
  </div>
</template>
<script>
import Tile from "./components/tile/Tile";

export default {
  name: "App",

  components: {
    Tile,
  },

  data() {
    return {
      tiles: ["Xoxo", "QQ", "Lol"],
    };
  },
};
</script>
<style lang="scss">
@import "./assets/scss/theme.scss";

.app {
  display: flex;
}
</style>
