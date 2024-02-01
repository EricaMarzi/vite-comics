<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
    name: 'DC Comics',
    components: {
        AppHeader,
        AppMain,
        AppFooter,
    }
}
</script>

<template>
    <AppHeader />
    <AppMain />
    <div class="bonus"></div> <!--Stai qui così ti vedo-->
    <AppFooter />
</template>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/*Generics */
body {
    background-color: #1c1c1c;
    font-family: 'Open Sans', sans-serif;
}

ul {
    list-style-type: none;
}

a {
    text-decoration: none;
}

/*Utility */
.container {
    width: 1280px;
    margin: 0 auto;
}

/*Per costruzione da togliere */
.bonus {
    height: 150px;
    background-color: #0282f9;
}
</style>