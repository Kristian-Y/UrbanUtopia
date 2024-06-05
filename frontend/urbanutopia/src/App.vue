<script setup>
    import Nav from './components/Nav.vue';
</script>

<template>
    <Nav></Nav>
    <main>
        <router-view></router-view> <!-- Where routed views are rendered -->
    </main>
</template>

<style scoped>
    
</style>

<style>
    html, body {
        margin: 0;
        width: 100%;
        height: 100%;
    }
</style>

<script>

</script>