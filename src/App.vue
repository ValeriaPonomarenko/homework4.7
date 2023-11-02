<template>
    <div :style="customStyles"></div>
</template>

<script>
export default {
  name: "App",
  computed: {
    customStyles(){
      return{
        width: "40px",
        height: "40px",
        backgroundColor: "red",
      }
    }
  }
};
</script>

<style>
</style>
