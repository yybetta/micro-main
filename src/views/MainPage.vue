<!--
 * @Description: 1
 * @Author: JZT.吴健
 * @Date: 2025-04-20 21:57:02
 * @LastEditors: JZT.吴健
 * @LastEditTime: 2025-11-14 08:47:44
-->
<template>
    <div>主应用页面</div>
    <div class="micro-app-container">
        <micro-app name="my-app" :url="subUrl" router-mode="state" iframe></micro-app>
    </div>
</template>

<script setup>
    import { ref } from 'vue'

    const subUrl = ref('http://localhost:5174/')
</script>

<style>
    micro-app {
        height: 500px;
    }
    .micro-app-container {
        margin: 10px;
        border: 1px solid #ddd;
        padding: 10px;
    }
</style>
