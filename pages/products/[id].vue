<template>
    <div>
       <h1>product Detailed Page</h1> 
       <h2>The product number is{{ route.params }}</h2>
    </div>
</template>

<script setup>
const route = useRoute()
</script>

<style lang="scss" scoped>

</style>