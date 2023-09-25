<script setup lang="ts">
import mainComponentVue from "./components/mainComponent.vue";
mainComponentVue
</script>

<template>
    <div>
        <header>
            <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

            <div class="wrapper">
                <h1>FastPay App</h1>
               
            </div>
        </header>
        <section>
            <main-component-vue></main-component-vue>
        </section>
    </div>
    
</template>

<style>
body {
    background-color: #000;
    display: flex;
    justify-content: flex-start;
}
</style>