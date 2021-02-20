<template>
  <div id="pokedex">
    <Pokedex />
  </div>
</template>

<script>
import Pokedex from "./components/Pokedex.vue";

export default {
  name: "App",
  components: {
    Pokedex,
  },
};
</script>

<style lang="scss" scoped>
#pokedex {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: calc(100vh);
  padding: 20px;

  background: url("./assets/florest.jpg");
  background-size: 100% 100%;
}
</style>
