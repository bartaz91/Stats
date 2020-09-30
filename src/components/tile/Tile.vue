<template>
  <div class="tile">I am {{ name }}</div>
</template>
<script>
export default {
  props: {
    name: {
      type: String,
      required: true,
    },
  },
};
</script>
<style lang="scss" scoped>
.tile {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 200px;
  height: 200px;
  background: lightblue;
  padding: 15px;
  margin: 20px;
  border-radius: 10px;
  text-align: center;
}
</style>
