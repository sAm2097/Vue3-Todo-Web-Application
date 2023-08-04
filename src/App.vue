<script setup>
import TodoHeader from "./components/TodoHeader.vue";
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
 <TodoHeader></TodoHeader>
<RouterView/>
</template>

<style lang="scss">
 @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@100;200;300;400;500;600;700;800;900&family=Rubik:ital,wght@0,300;0,400;0,500;0,700;0,800;1,300;1,400;1,500&display=swap');

 * {
  font-family: "Rubik", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>
