<script>
export default {
    name: 'AppHeader',
    data() {
        return {
            links: ['Characters', 'Comics', 'Movie', 'TV', 'Games', 'Collectibles', 'Videos', 'Fans', 'News', 'Shop']
        }
    }
}
</script>

<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="../assets/dc-comics-1/img/dc-logo.png" alt="">
            </div>

            <div>
                <ul class="navbar">
                    <li v-for="link in links"><a href="#">{{ link }}</a></li>
                </ul>
            </div>
        </div>
    </header>
</template>

<style scoped>
header {
    width: 100%;
    background-color: white;
}

.container {
    padding: 15px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo img {
    width: auto;
    height: 80px;
}

.navbar {
    display: flex;
    gap: 30px;

    text-transform: uppercase;
    letter-spacing: -1px;
    font-weight: 700;
    font-size: 14px;

}

.navbar a {
    color: #1c1c1c;
    padding: 45px 0;
}

.navbar a:hover {
    color: #0282f9;
    border-bottom: 3px solid #0282f9;
}
</style>