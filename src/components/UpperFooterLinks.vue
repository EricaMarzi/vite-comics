<script>
export default {
    name: 'UpperFooterLinks',
    props: {
        title: String,
        links: Array
    }
}
</script>

<template>
    <div class="col">
        <h3>{{ title }}</h3>
        <ul>
            <li v-for="link in links">
                <a href="#">{{ link.text }}</a>
            </li>
        </ul>
    </div>
</template>

<style scoped>
h3 {
    color: white;
    text-transform: uppercase;
}

.upper-footer a {
    color: #797979;
    font-size: 12px;
}
</style>