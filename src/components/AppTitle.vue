<template>
        <h1>{{ title }}</h1>
</template>

<script>
    export default {
        name : 'AppTitle',
        data() {
            return {
               title : 'La mia prima app con Vite!' 
            }
        }
    }
</script>

<style scoped>
    h1 {
        display: inline-block;
        background-image: linear-gradient(to right, violet, indigo, blue, green, yellow, orange, red, violet);
        -webkit-background-clip: text;
        background-clip: text;
        color: transparent;
        background-size: 200% 100%;
        animation: rainbow-text-animation 5s linear infinite;
    }
    @keyframes rainbow-text-animation {
        0% {
            background-position: 0 50%;
        }
        100% {
            background-position: 200% 50%;
        }
    }
</style>