<template>
    <button @click="increement">Increement</button>
    <p>{{data.count}}</p>
</template>

<script setup>
    import {reactive } from "vue";
    const data = reactive({
        count:0
    })
    function increement(){
        data.count++;
    }

</script>