<script>
export default {
    name: 'AppHeader'
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
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movie</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Collectibles</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">Fans</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
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

ul.navbar {
    display: flex;
    gap: 30px;

    text-transform: uppercase;
    letter-spacing: -1px;
    font-weight: 600;
    font-size: 14px;

}

.navbar a {
    color: #1c1c1c;
}
</style>