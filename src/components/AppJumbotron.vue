<template>
    <main>
        <AppTitle />
    </main>
</template>

<script>
import AppTitle from './AppTitle.vue';

    export default {
        name : 'AppJumbotron',
        components : {
            AppTitle
        }
    }
</script>

<style scoped>
    main {
        display: flex;
        justify-content: center;
        align-items: center;
        max-width: 664px;
        height: 307px;
        margin: 0 auto;
        background-image: url(../../public/jumbotron.png);
    }
</style>