<template>
    <p class="recommend-paragraf">
        {{ msg }}
    </p>
</template>

<script>
    export default {
        name: "RecommendParagraf",
        props: {
            msg: String
        },
        data(){
            return{
                page: undefined
            }
        }
    }
</script>

<style scoped>

</style>