<template>
    <div class="holder my-5 py-5">
        <div class="container">
            <h1 class="text-center my-3" style="font-weight: bold;">Properties 1</h1>

            <div class="row">
                <div class="col-md-6 col-lg-4 my-2">
                    <div class="prop">
                        <div class="prop-image" style="background-color: red; width: 100%;">
                            <router-link to="/property">
                                <img src="../assets/images/1.jpg" style="width:100%; height: 100%;" class="img-fluid" alt="">
                            </router-link>
                        </div>
                        <div class="hope  text-white"><i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i>SOLD OUT <i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i></div>

                        <div class="prop-detail text-white  p-2 my-3" style="font-weight: bold; color: rgb(235, 133, 16);">
                            <h1 style="font-weight: bold;">$65,000,000</h1>
                            <p>3 bedroom semi detached duplex with storage</p>
                            <div class="desc">
                                <div class="text-center"><p>Bed(s)</p><p>3</p></div>
                                <div class="text-center"><p>Bath(s)</p><p>5</p></div>
                                <div class="text-center"><p>Car(s)</p><p>2</p></div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-md-6 col-lg-4 my-2">
                    <div class="prop">
                        <div class="prop-image" style="width: 100%; background-color: red;">
                            <router-link to="/property">
                                <img src="../assets/images/6.jpg" style="width:100%; height: 100% !important"  alt="">
                            </router-link>
                        </div>
                        <div class="hope  text-white"><i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i>PRICE INCREASE <i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i></div>

                        <div class="prop-detail text-white  p-2 my-3" style="font-weight: bold; color: rgb(235, 133, 16);">
                            <h1 style="font-weight: bold;">$65,000,000</h1>
                            <p>3 bedroom semi detached duplex with storage</p>
                            <div class="desc">
                                <div class="text-center"><p>Bed(s)</p><p>3</p></div>
                                <div class="text-center"><p>Bath(s)</p><p>5</p></div>
                                <div class="text-center"><p>Car(s)</p><p>2</p></div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-md-6 col-lg-4 my-2">
                    <div class="prop">
                        <div class="prop-image">
                            <router-link to="/property">
                            <img src="../assets/images/7.jpg" style="width:100%; height: 100%;" class="img-fluid" alt="">
                            </router-link>
                        </div>
                        <div class="hope  text-white"><i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i>SOLD OUT <i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i></div>

                        <div class="prop-detail text-white  p-2 my-3" style="font-weight: bold; color: rgb(235, 133, 16);">
                            <h1 style="font-weight: bold;">$65,000,000</h1>
                            <p>3 bedroom semi detached duplex with storage</p>
                            <div class="desc">
                                <div class="text-center"><p>Bed(s)</p><p>3</p></div>
                                <div class="text-center"><p>Bath(s)</p><p>5</p></div>
                                <div class="text-center"><p>Car(s)</p><p>2</p></div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-md-6 col-lg-4 my-2">
                    <div class="prop">
                        <div class="prop-image">
                            <router-link to="/property">
                                <img src="../assets/images/3.jpg" style="width:100%; height: 100%;" class="img-fluid" alt="">
                            </router-link>
                        </div>
                        <div class="hope  text-white"><i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i>PRICE INCREASE <i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i><i class="fa fa-star mx-2"></i></div>

                        <div class="prop-detail text-white  p-3 my-3" style="font-weight: bold; color: rgb(235, 133, 16);">
                            <h1 style="font-weight: bold;">$65,000,000</h1>
                            <p>3 bedroom semi detached duplex with storage</p>
                            <div class="desc">
                                <div class="text-center"><p>Bed(s)</p><p>3</p></div>
                                <div class="text-center"><p>Bath(s)</p><p>5</p></div>
                                <div class="text-center"><p>Car(s)</p><p>2</p></div>
                            </div>
                        </div>
                    </div>
                </div>

                

                
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'Property1'
}
</script>

<style lang="scss" scoped>
    .prop{
        padding: 15px;
        background-color: none;
        border: 1px solid black;
    }
    .desc{
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .hope{
        // width: 50%;
        margin: 8px auto;
        // z-index: 10000000000000000000000000000000000000000000000000000000000000000000000;
        text-align: center;
        border-radius: 30px;
        background-color: rgb(235, 133, 16);
        cursor: not-allowed;
        padding: 7px;
    }
    .prop-image{
        height: 300px;
        overflow: hidden;
    }
    .prop-detail{
        background-color: rgb(235, 133, 16) !important;
        border-radius: 20px;
        text-align: center;
    }
</style>