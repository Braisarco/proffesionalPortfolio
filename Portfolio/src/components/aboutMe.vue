<script setup>
    import avatar from "./avatar.vue"
</script>

<template>
    <div class="aboutMe">
        <avatar/>
        <h1 class="aboutMeTitle">About me</h1>
    </div>
</template>

<style>
    .aboutMeTitle{
        
    }

    .aboutMe{
        margin-top: 100px;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
</style>