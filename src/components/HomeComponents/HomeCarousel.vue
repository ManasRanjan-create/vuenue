<template>
<div>
    <!-- carousel starts -->
    <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner .align-items-lg-center">
            <div class="carousel-item active">
                <img src="../../assets/h1.jpeg" class="w-100" alt="..." />
            </div>
            <div class="carousel-item">
                <img src="../../assets/h2.jpg" class="w-100" alt="..." />
            </div>
            <div class="carousel-item">
                <img src="../../assets/h5.jpg" class="w-100" alt="..." />
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
    <!-- carousel ends -->
</div>
</template>

<script>
export default {
    name:"HomeCarousel"
}
</script>

<style>

</style>
