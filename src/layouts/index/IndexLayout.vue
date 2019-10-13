<template>
    <p>External component content. {{ exampleData }} </p>
    <el-button type="primary">Primary button example</el-button>
</template>

<script>
    module.exports = {
        data: function () {
            return {
                exampleData: 'data from component'
            }
        }
    }
</script>

<style scoped>
    p {
        font-size: 2em;
        text-align: center;
    }
</style>