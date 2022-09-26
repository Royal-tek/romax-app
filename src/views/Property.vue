<template>
    <div class="holder my-5 py-5">
        <div class="container mt-5">
            <div class="row my-5">
                <div class="col-md-6">
                    <h1 class="text-center text-uppercase my-4" style="font-weight: bold;">3 Bedroom terrace duplex </h1>
                    <p class="text-center text-capitalize my-4" style="font-weight: bold;"><i class="fa fa-map-marker mx-2"></i>Oba Salemonu Oyebola Street, off Orchid road.</p>
                </div>
                <div class="col-md-6" style="border-left: 2px solid black;">
                    <h1 class="text-center text-uppercase mt-4" style="font-weight: bold;">$ 40,000,000</h1>
                    <p class="p-2 text-center text-white" style="background-color: rgb(235, 133, 16); width: 20%; margin: 0 auto; cursor: not-allowed; border-radius: 20px;">sold out</p>
                </div>
            </div>

            <div class="img-wrapper my-5">
                <div class="img-holder" :style="{backgroundImage:'url(../assets/images/4.jpg)'}">
                    <!-- <img src="../assets/images/2.jpg" style="width: 100% !important;" class="img-fluid img-responsive" alt=""> -->
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'Property'
}
</script>

<style lang="scss" scoped>
 .img-holder{
    background-position: center;
    background-size: cover;
    height: 500px;
    width: 100%;
 }
</style>