<script>
export default {
    name: 'AppFooter'
}
</script>

<template>
    <footer>
        <div class="container">

            <div class="upper-footer">
                <div class="footer-list">
                    <div class="col">

                        <h3>DC Comics</h3>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                        <h3>Shop</h3>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>

                    <div class="col">
                        <h3>DC</h3>
                        <ul>
                            <li><a href="#">Term Of Use</a></li>
                            <li><a href="#">Privacy policy (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPCS Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>

                    <div class="col">
                        <h3>Sites</h3>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD MAgazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
                        </ul>
                    </div>
                </div>
                <div class="logo-bg">
                    <img src="../assets/dc-comics-1/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>
        <div class="bottom-footer">

        </div>
    </footer>
</template>

<style scoped>
footer {
    height: 400px;
    background-image: url(../assets/dc-comics-1/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
}

/* Upper Footer */
.upper-footer {
    display: flex;

    position: relative;
}

.footer-list {
    height: 400px;
    width: 40%;
    padding-top: 50px;

    display: flex;
    gap: 10px;
}

.col {
    width: calc(100% / 3);
}

h3 {
    color: white;
    text-transform: uppercase;
}

.upper-footer a {
    color: grey;
    font-size: 12px;
}

/*DC Logo */
.logo-bg img {
    position: absolute;
    right: 0;
    top: -90px;

}

/*Bottom Footer */
.bottom-footer {
    height: 100px;
    background-color: #303030;

    position: relative;
    z-index: 1;
}
</style>