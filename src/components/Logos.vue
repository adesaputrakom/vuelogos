<template>
    <div class="logo-wrapper">
        <h2 class="title-header">Find Best Log</h2>
        <div class="item-logos">
            <img class="logo" src="../assets/react-logo.png" alt="React logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/logo.png" alt="Vue logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/codeigniter-logo.png" alt="Codeigniter logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/laravel-logo.png" alt="Laravel logo">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/lumen-logo.png" alt="lumen logo">
        </div>
    </div>
</template>

<script>
    export default{
        name : 'LogosItem'
    }
</script>

<style scoped>
    .title-header{
        margin-bottom: 80px;
        text-align: left;
    }

    .logo-wrapper{
        width: 65%;
        overflow: hidden;
        margin: auto;
    }

    .item-logos{
        float: left;
        margin-right: 20px;
        margin-bottom: 20px;
        width: 150px;
        height: 150px;
    }

    .item-logos .logo{
        width: 150px;
        height: 150px;
    }
</style>