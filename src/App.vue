<script>
import AppHeader from './components/AppHeader.vue';
import AppHero from './components/AppHero.vue';
import AppCards from './components/AppCards.vue';

export default {
    name: 'App',
    components: {
        AppHeader,
        AppHero,
        AppCards,
    }
}
</script>

<template>
    <AppHeader />
    <AppHero />
    <AppCards />

    <main>
        <div id="who_we_are_section" class="p-5 mb-4">
            <div class="container-fluid py-5">
                <div class="">
                    <p>Instrumental rock</p>
                    <h1 class="">Music in this video</h1>

                </div>
            </div>



        </div>

    </main>

    <footer></footer>
</template>

<style lang="scss">
@use './assets/scss/partials/variables' as *;

body {
    font-family: 'Oswald', sans-serif;
}
</style>
