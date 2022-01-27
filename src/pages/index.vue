<script setup lang="ts">
// import { useUserStore } from '~/stores/user'
// const user = useUserStore()
// const name = ref(user.savedName)
// const router = useRouter()
// const go = () => {
//   if (name.value)
//     router.push(`/hi/${encodeURIComponent(name.value)}`)
// }
// const { t } = useI18n()
</script>

<template>
  <div class="main">
    <div class="container">
      <h1>Monsteria</h1>
    </div>
  </div>
</template>

<route lang="yaml">
meta:
  layout: home
</route>

<style scoped>
h1 {
  position: absolute;
  top: 0;
  right: 0;
  margin-top: 1%;
  margin-right: 11%;
  border-radius: 2rem;
  font-size: 19rem;
  color: rgba(0, 0, 0, 0.356);
  font-family: Rubik;
}
@font-face {
  font-family: "Rubik";
  src: url(/RubikBeastly-Regular.ttf);
}
</style>
