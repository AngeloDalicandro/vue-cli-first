<template>
    <div class="jumbo">
        <img :src="url" alt="Zoro">
    </div>
</template>

<script>
export default {
    name: "MyJumbo",
    data() {
        return {
            url: "https://www.tomshw.it/images/images/2021/08/one-piece-1023-182375.jpg"
        }
    },
}
</script>

<style lang="scss" scoped>
    img {
        width: 100%;
    }
</style>