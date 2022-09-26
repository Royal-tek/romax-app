<template>
    <div class="holder my-5 py-5">
        <div class="container mt-5">
            <div class="row my-5">
                <div class="col-md-6">
                    <h1 class="text-center text-uppercase my-4" style="font-weight: bold;">3 Bedroom terrace duplex </h1>
                    <p class="text-center text-capitalize my-4" style="font-weight: bold;"><i class="fa fa-map-marker mx-2"></i>Oba Salemonu Oyebola Street, off Orchid road.</p>
                </div>
                <div class="col-md-6 b" style="border-left: 2px solid black;">
                    <h1 class="text-center text-uppercase mt-4" style="font-weight: bold;">$ 40,000,000</h1>
                    <p class="p-2 text-center text-white" style="background-color: rgb(235, 133, 16); width: 50%; margin: 0 auto; cursor: not-allowed; border-radius: 20px;">sold out</p>
                </div>
            </div>

            <div class="img-wrapper my-5">
                <div class="img-holder" >
                    <img src="../assets/images/5.jpg" class="img-fluid img-responsive" alt="">
                </div>
                <div class="my-5">
                    <h3 style="font-weight: bold;">Property Description</h3>
                    <p class="text-dark" style="font-weight: bold;">Built with the user’s comfort as the most important consideration, this unit offers maximum satisfaction for the owner. Spaces are large enough to allow luxurious lifestyle and finishing. This home is designed to match varying modern lifestyles with luxury living at an affordable price.</p>
                </div>
                <div class="my-5">
                    <h3 style="font-weight: bold;">Features</h3>
                    <ul style="font-weight: bold;">
                        <li><P>CCTV</P></li>
                        <li><P>DWARF FENCING</P></li>
                        <li><P>GATED ESTATE</P></li>
                        <li><P>RECREATIONAL AREA</P></li>
                        <li><P>24 HOUR SECURITY</P></li>

                    </ul>
                </div>
                <div class="my-5">
                    <h3 style="font-weight: bold;">Payment Plan</h3>
                    <p class="text-dark" style="font-weight: bold;">50% Initial Deposit with Balance spread within 3 months.</p>
                </div>

                <div class="my-5">
                    <h3 style="font-weight: bold;">Contact Number</h3>
                    <p class="text-dark" style="font-weight: bold;">09013750171.</p>
                    <h3 style="font-weight: bold;">Toll Free Hotline</h3>
                    <p class="text-dark" style="font-weight: bold;">07000076629.</p>
                </div>

                <div class="my-5">
                    <h3 style="font-weight: bold;">Property Details</h3>
                    <div class="row my-3" style="font-weight: bold;">
                        <div class="col-lg-3 col-md-6 my-2">
                            <div>
                                <h5>Property type</h5>
                                <p>Terraced Duplex</p>
                            </div>
                        </div>

                        <div class="col-lg-3 col-md-6 my-2">
                            <div>
                            <h5>Bedrooms</h5>
                            <p>3</p>
                        </div>
                        </div>

                        <div class="col-lg-3 col-md-6 my-2">
                            <div>
                            <h5>Bathrooms</h5>
                            <p>3.5</p>
                        </div>
                        </div>

                        <div class="col-lg-3 col-md-6 my-2">
                            <div>
                            <h5>Car Parking</h5>
                            <p>1</p>
                        </div>
                        </div>
                        
                        
                        
                        
                    </div>
                </div>
            </div>

            
                <div class="row my-3">
                    <div class="col-lg-6 mesh ">
                        <div class="p-5 my-3">
                            <p><i class="fa fa-bath"></i></p>
                            <p>All bathrooms are equipped with state of the art fixtures with the master bathroom particularly fitted with Jacuzzi.​</p>
                        </div>
                    </div>
                    <div class="col-lg-6 mesh">
                        <div class="p-5 my-3">
                            <p><i class="fa fa-radio"></i></p>
                            <p>The kitchen boasts of well fitted cabinets with extractor hood over the cooker place, Split unit A/C, Gas stove, Oven and Microwave.​</p>
                        </div>
                    </div>
                    
                </div>
                <div class="row my-3">
                    <div class="col-lg-6 mesh ">
                        <div class="p-5 my-3">
                            <p><i class="fa fa-camera"></i></p>
                            <p>All homes come fully equipped with CCTV, Speakers and Video Door Phone for effective survelliance and monitoring.​</p>
                        </div>
                    </div>
                    <div class="col-lg-6 mesh">
                        <div class="p-5 my-3">
                            <p><i class="fa fa-tree"></i></p>
                            <p>Proximity to existing recreational services. Such as Lekki Conservation Centre and Shoprite mall.​</p>
                        </div>
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
    height: 600px;
    width: 100%;
    overflow: hidden;

    img{
        width: 100%;
        
    }
 }
 .mesh{
    font-weight: bold;

    i{
        font-size: 50px;
    }

    div{
        display: flex;
        flex-direction: column;
        align-items: center;
        color: #fff;
        justify-content: center;
        background-color: rgb(235, 133, 16);

    }
 }
 .bing{
    display: flex;
    align-items: center;
    justify-content: space-between;
    text-align: center;
 }
 @media(max-width: 850px){
    .b{
        border-left: none !important;
    }
 }
</style>