<template>
  <header>
    La mia prima app con Vue CLI!
  </header>
</template>



<script>  

export default {
  name: 'TitleComp',
}
</script>

<style scoped>

  header{
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100px;
    background-color: rgb(198, 255, 255);
    font-size: 2vw;
    color: rgb(19, 138, 138);
    text-shadow: 3px 3px 15px rgb(19, 138, 138);
  }

</style>