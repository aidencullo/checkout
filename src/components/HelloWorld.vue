<script setup lang="ts">

import { ref } from 'vue';

const message = ref("I had an excellent experience with Harley and Sons!");
  
</script>

<template>
<h1>Harley and Sons LLC</h1>

<div class="card">

  <div class="prompt">
  <span>What was your experience with Harley and Sons?</span>
  </div>
  
  <textarea v-model="message"></textarea>
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
