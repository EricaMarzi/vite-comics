<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'
import { comics, footerLinks } from './data/index.js'

export default {
    name: 'DC Comics',
    data() {
        return {
            footerLinks,
            comics
        }
    },
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
    <AppFooter :footerLinks="footerLinks" />
</template>


<style lang="scss">
@use './assets/scss/style.scss'
</style>