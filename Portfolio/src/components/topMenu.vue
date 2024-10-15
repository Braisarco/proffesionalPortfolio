<script setup>    
    import proffilePicture from "./topMenuItems/proffilePicture.vue"
    import languageSelector from "./topMenuItems/languageSelector.vue"
</script>

<template>
    <div class="menu">
        <proffilePicture/>
        <languageSelector/>
    </div>
</template>

<style>
    .menu{
        top: 0;
        padding: 10px;
        display: flex;
        flex-direction:row;
        justify-content: space-between;
        height: auto;
        max-height: 100px;
        width: 100%;
        background-color: #010409;
    }
</style>