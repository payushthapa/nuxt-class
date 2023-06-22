<template>
    <div>
      <div class="container">
        <div class="row">
            <div class="col-md-6">
                <img :src="product.image[0]" alt="" height="400px">
                <h1>{{ product.title }}</h1>
                <p>{{ product.description }}</p>
                <p>{{ product.prize }}</p>
            </div>
        </div>
      </div>
    </div>
</template>

<script setup>
const route = useRoute();
const {data:product} = await useFetch(`https://api.escuelajs.co/api/v1/products/${route.params.id}`);
</script>

<style scoped>

</style>