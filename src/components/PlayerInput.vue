<script setup>
defineProps({
  playerNumber: {
    type: String,
    required: true,
  },
});
</script>
<template>
    <label for="inputPlayer">Joueur {{playerNumber.toString()}}</label>
    <input type="text" id="inputPlayer">
</template>
<style scoped>

</style>