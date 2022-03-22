<template>
    <main>
        <h1 class="title">Advice <span>#18</span></h1>
        <p class="quote">
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem
            ipsum dolor sit amet consectetur adipisicing elit. Officia"
        </p>
    </main>
</template>

<script>
export default {
    name: 'advice-component',
}
</script>

<style scoped lang="scss">
main {
    background-color: $bg-quote;
    margin: 20px;
    padding: 55px;
    max-width: 600px;
    text-align: center;
    border-radius: 15px;

    .title {
        color: $primary;
        font: $title;
        text-transform: uppercase;
        letter-spacing: 4.16px;
    }

    .quote {
        color: $secondary;
        font: $quote;
        margin: 40px;
    }
}
</style>
