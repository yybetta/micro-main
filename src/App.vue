<template>
    <div class="app-container">
        <router-view></router-view>
    </div>
</template>

<style lang="scss">
    @use './styles/index.scss';

    .app-container {
        position: relative;
        width: 100%;
        height: 100%;
    }
</style>
