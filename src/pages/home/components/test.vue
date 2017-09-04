<template>
    <div>
        {{ d }}
    </div>
</template>

<script>
    const test = {
        name: 'test',
        data: function () {
            return {
                d: 'you data from test.vue file'
            }
        }
    }

    export default test
</script>

<style lang="scss" scoped>

</style>
