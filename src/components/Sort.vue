<template>
    <div>
        <h3>Sort By</h3>
        <select v-model="sort.sortBy">
            <option>None</option>
            <option value="pokemon">Name(A-Z)</option>
            <option value="defense">Defense(High-Low)</option>
            <option value="attack">Attack(High-Low)</option>
        </select>  
    </div>

</template>
<script>
    export default {


        props: ['sort']
    }
</script>
<style scoped>
    div {
        
        display: flex;
        flex-wrap: wrap;
        align-items: center;
    }
    h3 {
        margin-left: 10px;
        margin-right: 10px;
    }
</style>