<script>
export default {
    name: 'AppMain',
    props: {
        comics: Array
    }
}
</script>

<template>
    <main class="container">
        <div class="row">
            <div class="col">
                <div class="card" v-for="(comic, i) in comics" :key="i">
                    <img :src="comic.thumb" :alt="comic.series">
                    <label>
                        <div class="title">{{ comic.series }}</div>
                    </label>
                </div>
            </div>
        </div>
    </main>
</template>

<style scoped>
main {
    height: 850px;
}

.row {
    padding: 50px 0;
    width: 100%;
}

.col {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    margin: 0 -1rem;
}

.card {
    width: calc(100% / 6 - 2rem);
    height: 360px;


}

img {
    width: 100%;
    height: auto;
    display: block;
}

label .title {
    margin-top: 10px;
    text-transform: uppercase;
    color: white;

}
</style>