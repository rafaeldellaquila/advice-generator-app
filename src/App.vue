<template>
    <advice-component />
</template>

<script>
import AdviceComponent from './components/AdviceComponent.vue'

export default {
    name: 'App',

    components: {
        'advice-component': AdviceComponent,
    },
}
</script>

<style lang="scss">
#app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: $bg;
    height: 100vh;
    width: 100vw;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
}
</style>
