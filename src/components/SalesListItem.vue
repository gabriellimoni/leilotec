<template>
    <router-link :to="`/leilao`">
        <div class="sale-item">
            Leilão Mazicrazzy 28/09/2020 14:30
        </div>
    </router-link>
</template>

<script>
export default {
    name: 'sales-list-item'
}
</script>

<style lang="scss" scoped>
.sale-item {
    background: #f8f8f8;
    padding: 8px 12px;
    margin: 7px 0;
    border-radius: 6px;
    font-size: 20px;
    cursor: pointer;
    transition: .1s all;
}
.sale-item:hover {
    transform: scale(1.01);
}
.sale-item:active {
    transform: scale(1.03);
}
a {
    text-decoration: none;
    color: #333;
}
</style>
