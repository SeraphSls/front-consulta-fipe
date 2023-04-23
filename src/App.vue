<script setup>
import navComponent from './components/navComponent.vue'
</script>

<template>
  <header>
    <navComponent></navComponent>
  </header>
  <body>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </body>

  <RouterView />
</template>

<style scoped>

</style>
