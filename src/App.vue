<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'

export default {
    name: 'DC Comics',
    components: {
        AppHeader,
        AppMain,
    }
}
</script>

<template>
    <AppHeader />
    <AppMain />
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
    color: #1c1c1c;
    text-decoration: none;
}

/*Utility */
.container {
    width: 1280px;
    margin: 0 auto;
    height: 100px;
    /*da togliere a fine costruzione */
}
</style>