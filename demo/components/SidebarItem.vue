<template>
    <div>
        {{ test }}
    </div>
</template>

<script>
    export default {
        props: {
            test: {
                type: String,
                default: 'test'
            }
        },
        data() {
            return {
                //
            }
        },
    }
</script>

<style scoped>

</style>
