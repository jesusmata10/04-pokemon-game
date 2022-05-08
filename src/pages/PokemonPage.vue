<template>
  <h1>¿Quién es este Pokemon?</h1>

  <!--TODO: img-->
  <PokemonPicture :pokemonId='4' :showPokemon="true"/>
  <!--TODO: Opciones-->

  <PokemonOptions />
</template>

<script>
import PokemonPicture from "@/components/PokemonPicture.vue";
import PokemonOptions from "@/components/PokemonOptions.vue";

export default {
  name: "App",
  components: {

    PokemonPicture,
    PokemonOptions,
  },
};
</script>