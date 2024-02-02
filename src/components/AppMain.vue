<script>
export default {
    name: 'AppMain'
}
</script>

<template>
    <main class="container">
        <div class="row">
            <div class="col">
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>

                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
                <div class="card"></div>
            </div>
        </div>
    </main>
</template>

<style scoped>
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
    margin: 1ren;
    width: calc(100% / 6 - 2rem);
    height: 190px;
    background-color: white;
}
</style>