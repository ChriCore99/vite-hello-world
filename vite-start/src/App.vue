<script>
export default{
    data(){
        return{
            message: "La mia prima volta con VITE"
        }
    }
}
</script>

<template>
<div id="AppTitle">
    <h1 class="center">
        {{ message }}
    </h1>
</div>

<div id="AppHero">
    <img src="../public/1618197067vitejs.webp" alt="">
</div>
</template>

<style>
.center{
    text-align: center;
}
</style>
