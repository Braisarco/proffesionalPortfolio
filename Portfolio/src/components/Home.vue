<script setup>
    import topMenu from './topMenu.vue'
    import aboutMe from './aboutMe.vue';
</script>

<template>
    <div class = 'application-body'>
        <topMenu/>
        <aboutMe/>
    </div>
</template>

<style>
    .application-body{  
        display: flex;
        width: 100%;
        flex-direction: column;
        background-color: #181818;
    }
</style>