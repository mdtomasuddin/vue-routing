<script setup>
import { useRoute } from 'vue-router';

const route=useRoute();
const name=route.params.name;
</script>

<template>

    <div>
        <h1>this is a person page </h1>
        <p>Name : {{ name }}</p>
        <p>directly access Name : {{ $route.params.name }}</p>
    </div>
</template>

<style scoped></style>