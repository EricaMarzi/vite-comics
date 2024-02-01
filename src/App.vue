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


<style lang="scss">
@use './assets/scss/style.scss'
</style>