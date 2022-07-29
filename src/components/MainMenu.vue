<script setup lang="ts">

const props = defineProps({
    icon: String,
    title: String
})
</script>

<template>
    <div class="card-menu">
        <img :src="`src/assets/${icon}`" />
        <h1>{{ title }}</h1>
    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Lacquer&display=swap');

.card-menu {
    width: 6.25rem;
    height: 8.625rem;

    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;

    cursor: pointer;
    margin-left: 1.563rem;
    margin-right: 1.563rem;
}

.card-menu img {
    width: 6.25rem;
    height: 6.25rem;
}

.card-menu h1 {
    font-family: 'Lacquer', cursive;
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 24px;
    text-align: center;

    color: #000505;
}
</style>