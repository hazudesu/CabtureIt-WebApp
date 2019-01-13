<template>
    <div style="position:relative; bottom:80px; left:370px">
        <table style="table-layout: fixed; width: max-content;">
            <tr >
                <header class="header">
                    <img alt="CabtureIt logo" src="./bantestclr.png" align="center"/>
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
        color: aqua;
        text-align: center;
        padding: 0;
        margin-top: 0;
        height: 100px;
        width: max-content;
    }
    .header a{
        height: 0;
        width: max-content;
        background: white;
    }
</style>
