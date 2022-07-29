<script setup lang="ts">
import MainMenu from "./MainMenu.vue";
</script>

<template>
    <div class="main-page">
        <img class="logo" src="../assets/ball.png" />

        <div class="menus">
            <MainMenu :icon="'jordan.png'" :title="'Jogadores'"></MainMenu>
            <MainMenu :icon="'jersey.png'" :title="'Times'"></MainMenu>
            <MainMenu :icon="'basketball.png'" :title="'Números'"></MainMenu>
        </div>
    </div>
</template>

<style>
.main-page {
    width: 100vw;
    height: 100vh;
    background: #F9A03F;
    display: flex;
    align-items: center;
    justify-content: center;
}

.main-page .logo {
    position: absolute;
    width: 6.25rem;
    height: 6.25rem;
    left: 2.5rem;
    top: 2.5rem;
}

.menus {
    display: flex;
    align-items: center;
    justify-content: center;

}
</style>