<template>
  <div>
    <label for="age-input">Enter your age:</label>
    <input type="number" id="age-input" v-model="age" />

    <p v-if="age >= 18">You are old enough to vote.</p>
    <p v-else>You are not old enough to vote.</p>
  </div>
</template>

<script setup>

</script>

<style scoped>
div{
  

}
</style>
