<template>
    <div>
        <div class="card" style="width: 18rem;">
                            <div class="image-box">
                                <img src="https://cdn.pixabay.com/photo/2023/06/07/20/34/ball-8048205__340.jpg" alt="">
                            </div>
                            <div class="card-body">
                                <h5 class="card-title">Card title</h5>
                                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                                <a href="#" class="btn btn-primary">Go somewhere</a>
                            </div>
                        </div>
                        </div>
</template>

<script setup>

</script>

<style scoped>
img {
    filter: grayscale();
    transition: 1s;
}

img:hover {
    filter: none;
    transform: scale(2);
}
.image-box{
    overflow: hidden;
}
</style>