<template>
    <SideLayout class="sidebar">
        <div class="grid">
            <h1><img alt="publication logo" src="./pubclr.png"></h1>
        </div>
    </SideLayout>
</template>

<script>
    export default {
        name: "SideLayout.vue"
    }
</script>

<style scoped>
    .grid{
        display: grid;
        float: left;
        width: 300px;
        height: max-content;
    }

    .sidebar{
        border: black;
        border-collapse: collapse;
        font: ;
    }
</style>
