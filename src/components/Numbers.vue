<template>
    <div>
        <span v-for="(n, key) in 10" :key="key">{{ n }} </span>
    </div>
</template>

<script>
    export default {
        name: "NumbersComponent",
    }
</script>

<style lang="scss" scoped>

</style>