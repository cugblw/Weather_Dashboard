<template>
    <div>
        <p>This child components of Content.vue are:</p>
        <ul>
            <li v-for="child in chindComponents">{{child}}</li>
        </ul>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                childComponents: ['TempVarChart.vue', 'Hightlights.vue']
            }
        },
        methods: {

        },
        computed: {

        }
    }
</script>

<style>

</style>