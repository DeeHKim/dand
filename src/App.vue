<template>
<div id="app">
    <NavBar />
    <router-view/>
</div>
</template>

<script>
import NavBar from '@/components/shared/NavBar'

export default {
    name: 'app',
    components: {
        NavBar
    }
}
</script>

<style>
body {
    margin: 0;
}
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
}
</style>
