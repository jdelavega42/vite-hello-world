<script>
export default {
    name: "AppHero",
    data() {
        return {
            phrase: "Powered by"
        }
    }
}
</script>

<template>
    <div class="jumbotron">
        <p> {{ phrase }}</p>
        <img src="../assets/vue.svg" alt="">
    </div>
</template>

<style>
.jumbotron {
    background-color: lightcoral;
    height: 25vh;
    padding: 1rem;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>