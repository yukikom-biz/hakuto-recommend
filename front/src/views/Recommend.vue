<template>
    <section class="recommend">
        <RecommendTextMain/>
    </section>
</template>
<script>
    import RecommendTextMain from "../components/RecommendTextMain";

    export default {
        name: "Recommend",
        components: {
            RecommendTextMain
        },
        data() {
            return {
                page: undefined,
                user: undefined
            }
        },
        created() {

        },
        methods: {}
    }
</script>

<style scoped lang="scss">

</style>