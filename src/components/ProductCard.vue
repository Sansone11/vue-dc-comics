<template>
    <article class="card">
        <img :src="thumb" :alt="series">
        <h2>{{ series }}</h2>
    </article>
</template>

<script>

export default {
    props: {
        thumb: String,
        series: String,
    },
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.card {
    text-align: center;

    h2 {
        color: white;
    }
}
</style>
