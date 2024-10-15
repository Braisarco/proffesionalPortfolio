<script setup>    
    import esIcon from '../icons/esIcon.vue';
    import galIcon from '../icons/galIcon.vue';
    import enIcon from '../icons/enIcon.vue';
</script>

<template>
    <div class="selector">
        <galIcon />
        <esIcon />
        <enIcon />
    </div>
</template>

<style>
    .selector{
        display: flex;
        flex-direction: row;
        justify-content:space-around;
        align-items: center;
    }
</style>