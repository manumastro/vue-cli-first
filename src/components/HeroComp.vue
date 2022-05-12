<template>
  <section>
    Questo è il JumboTron
  </section>
</template>

<script>
export default {
  name: 'HeroComp',
}
</script>

<style scoped>
  section{
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3vw;
    color: rgb(19, 138, 138);
    text-shadow: 3px 3px 30px rgb(19, 138, 138);
    height: calc(100vh - 100px);
    background-color: rgb(172, 255, 255);
  }
</style>