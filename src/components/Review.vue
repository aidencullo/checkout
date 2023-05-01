<script setup lang="ts">

import { ref } from 'vue';

const yes = ref(false);
const no = ref(false);

</script>

<template>

<div class="card" v-if="!yes && !no">

  <div class="prompt" >
  <h2>Did you have a good experience with company X?</h2>
  </div>

  <button @click="yes=!yes">Yes</button>
  <button @click="no=!no">No</button>

</div>

<div class="card" v-if="yes">

  <div class="prompt" >
  <h2>Redirecting to company X website...</h2>
  </div>

</div>

<div class="card" v-if="no">

  <div class="prompt" >
  <h2>What could company X have done better?</h2>
  </div>
  <input>

</div>

</template>

<style scoped>
.read-the-docs {
    color: #888;
}

.prompt {
    padding: 10px;
}


</style>
