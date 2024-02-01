<script>
import AppHeader from './components/AppHeader.vue'

export default {
    name: 'DC Comics',
    components: {
        AppHeader
    }
}
</script>

<template>
    <AppHeader />
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
</style>