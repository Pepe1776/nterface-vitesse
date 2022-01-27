<template>
  <div class="nav">
    <div class="nav-icons">
      <twemoji-potted-plant class="icon-btn" />
      <emojione-fallen-leaf class="icon-btn" />
      <noto-potted-plant class="icon-btn" />
    </div>
  </div>
</template>
<script lang="ts" setup>
</script>
<style>
.nav {
    position: fixed;
    top: 0;
    left: 0;
    display: flex;
    height: 100vh;
    width: 9%;
    background-color: rgba(0, 0, 0, 0.486);
}
.nav-icons {
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    font-size: 10rem;
}
.nav-icons-icon {}
</style>
