<script setup lang="ts">
  import Review from './components/Review.vue'
</script>

<template>
<div class="bg">
<Review companyName="company Y" companyLink="[company Y link]"/>
  </div>
</template>

<style scoped>
.logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
}
.logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
    filter: drop-shadow(0 0 2em #42b883aa);
}

</style>
