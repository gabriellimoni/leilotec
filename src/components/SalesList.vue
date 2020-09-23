<template>
    <div class="sale-list">
        <sales-list-item /> 
    </div>
</template>

<script>
import SalesListItem from './SalesListItem.vue'
export default {
    name: 'sales-list',
    components: {
        SalesListItem,
    },
}
</script>
