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
        <div id="who_we_are_section" class="p-5">
            <div class="container-fluid align-items-center d-flex flex-column py-5">
                <div class="">
                    <h6>Who We Are</h6>
                    <h1 class="">Sense the jazz</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur et expedita dignissimos? Illum
                        debitis dolores dicta quam doloribus inventore error unde accusantium, architecto vel sapiente quis
                        expedita hic provident omnis. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Natus illum
                        eveniet iure sapiente, sunt totam, sed earum, soluta minima maxime nihil quibusdam! Quos voluptate
                        eaque impedit eum minima maxime ut. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eos
                        omnis, odit facere voluptatibus illo tempora aperiam soluta eaque error, culpa expedita, vel iure
                        dolores sunt porro earum? Eaque, deserunt tempore.</p>
                </div>
                <div>
                    <button type="button" class="btn btn_cstm btn-lg">read more</button>
                </div>

            </div>



        </div>


    </main>

    <footer>
        <div class="footer_top d-flex">

            <div class="col">
                <img src="./assets/img/instagram_img1.jpg" alt="">
            </div>
            <div class="col">
                <img src="./assets/img/instagram_img2.jpg" alt="">
            </div>
            <div class="col">
                <img src="./assets/img/instagram_img3.jpg" alt="">
            </div>
            <div class="col">
                <img src="./assets/img/instagram_img4.jpg" alt="">
            </div>
            <div class="col">
                <img src="./assets/img/instagram_img5.jpg" alt="">
            </div>
            <div class="col">
                <img src="./assets/img/instagram_img6.jpg" alt="">
            </div>
            <div class="col">
                <img src="./assets/img/instagram_img7.jpg" alt="">
            </div>
            <div class="col">
                <img src="./assets/img/instagram_img8.jpg" alt="">
            </div>

        </div>

        <div class="footer_mid"></div>
        <div class="footer_bot"></div>
    </footer>
</template>

<style lang="scss">
@use './assets/scss/partials/variables' as *;

body {
    font-family: 'Oswald', sans-serif;
}
</style>
