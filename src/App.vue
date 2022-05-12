<template>
  <div>
    <TitleComp />
    <HeroComp />
  </div>
</template>

<script>

import TitleComp from './components/TitleComp.vue';
import HeroComp from './components/HeroComp.vue';

export default {
  name: 'App',
  components: {
    TitleComp,
    HeroComp
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body{
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
</style>
