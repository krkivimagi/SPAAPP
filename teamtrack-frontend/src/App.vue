<template>
    <Navbar />
    <router-view />
    
</template>

<script setup lang="ts">
    import {defineProps} from "vue";
    import Navbar from "./components/Navbar.vue";
    defineProps<{ isAthlete: Boolean, hasChosen: Boolean}>();
</script>


