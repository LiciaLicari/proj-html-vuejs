<script>
import AppHeader from './components/AppHeader.vue';
import AppCards from './components/AppCards.vue';

export default {
    name: 'App',
    components: {
        AppHeader,
        AppCards,
    }
}
</script>

<template>
    <AppHeader />
    <AppCards />

    <main>




    </main>

    <footer></footer>
</template>

<style lang="scss">
@use './assets/scss/partials/variables' as *;

body {
    font-family: 'Oswald', sans-serif;
}</style>
