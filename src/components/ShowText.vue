<template>
    <div>
        <button @click="isVisible = !isVisible">Показать</button>
        <div class="text" v-if="isVisible">Скрыто</div>
        <div class="textTwo" v-else>Отображено</div>
    </div>
</template>

<script>
    
    export default {
        name: "ShowText",

        data: () => ({
            isVisible: true,
            activeBtn: true,
        }),
    }
</script>

<style lang="scss" scoped>

</style>