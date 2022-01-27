<script setup lang="ts">
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'Monsteria',
  meta: [
    { name: 'description', content: 'Design => Deployment' },
  ],
})
</script>

<template>
  <div class="body">
    <router-view />
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  font-size: 62.5%;
}
body {
background-image: url(/jackie-dilorenzo-RyLsRzy9jIA-unsplash.jpg);
background-size: cover;
}
.body {
  background-color: rgba(14, 85, 2, 0.664);
  height: 100vh;
}
</style>
