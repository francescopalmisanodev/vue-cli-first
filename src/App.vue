<template>
<header>
  <Title/>
</header>
</template>

<script>
 import Title from "@/components/Title.vue";
 export default {
   name:"App",
   components: {
     Title,
   }
 } 
</script>

<style lang="scss">
header {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 20vh;
}
</style>
