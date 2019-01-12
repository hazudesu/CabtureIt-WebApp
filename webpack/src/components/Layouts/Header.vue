<template>
    <div style="position:relative; bottom:100px; left:250px">
        <table style="table-layout: fixed; width: max-content">
            <tr height="100">
                <header class="header">
                    <img alt="CabtureIt logo" src="./bantest.png" align="center"/>
                </header>
            </tr>
        </table>
    </div>
</template>

<script>
    export default {
        name: "Header"

    }
</script>

<style scoped>
    .header{
        background: #ffffff;
        color: aqua;
        text-align: center;
        padding: 0;
        margin-top: 0;
        height: 100px;
    }
    .header a{
        height: 0px;
        width: max-content;
    }
</style>
