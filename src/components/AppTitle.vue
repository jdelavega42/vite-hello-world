<script>
export default {
    name: "AppTitle",
  data(){
    return {
      title: "La mia prima app con Vite!!"
    }
  }
}
</script>

<template>
  <h1> {{ title }}</h1>
</template>

<style>
    h1 {
        text-align: center;
        padding: 1rem;
        color: red;
    }
</style>