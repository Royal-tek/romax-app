        <template>
    <div class="about mt-5 py-4">
        <section id="contact" class="p-5">
        <div class="container-fluid" style="width: 90%">
            <div class="row" style="height: 100%">
            <div class="col-md-4 col-sm-12 my-4 discuss text-light">
                <h1
                class="my-3 text-capitalize hhh"
                style="font-weight: bold; font-size: 50px"
                >
                Register your Interest
                </h1>
                <h5 class="my-3" style="font-weight: bold">
                Fill out the form, or call us to Schedule an Inspection.
                </h5>
                <h5 class="my-3" style="font-weight: bold">Project Locations :</h5>

                <p class="mt-1 mb-3" style="font-weight: bold">
                Harris Drive, Orchid Road, Ajiwe.
                </p>
                <h5 class="my-3" style="font-weight: bold">
                45A Alternative Route, Chevron Drive, Lekki, Lagos.
                </h5>
                <h5 class="my-3" style="font-weight: bold">Sales@romax.com</h5>
                <h5 class="my-3" style="font-weight: bold">07000076629</h5>
            </div>
            <div class="col-md-8 col-sm-12 my-4 text-center form">
                <form class="form">
                <div class="row">
                    <div class="col-md-6 col-sm-12">
                    <div class="form-group mx-3 my-2">
                        <input
                        type="text"
                        class="form-control shadow-none p-2"
                        placeholder="FirstName"
                        />
                    </div>
                    </div>
                    <div class="col-md-6 col-sm-12">
                    <div class="form-group mx-3 my-2">
                        <input
                        type="text"
                        class="form-control shadow-none p-2"
                        placeholder="LasttName"
                        />
                    </div>
                    </div>
                </div>

                <div class="row">
                    <div class="col-md-6 col-sm-12">
                    <div class="form-group mx-3 my-2">
                        <input
                        type="text"
                        class="form-control shadow-none p-2"
                        placeholder="Email"
                        />
                    </div>
                    </div>
                    <div class="col-md-6 col-sm-12">
                    <div class="form-group mx-3 my-2">
                        <input
                        type="number"
                        class="form-control shadow-none p-2"
                        placeholder="Phone Number"
                        />
                    </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-12">
                    <div class="form-group mx-3 my-2">
                        <input
                        type="text"
                        class="form-control shadow-none p-2"
                        placeholder="Address"
                        />
                    </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-12">
                    <div class="form-group mx-3 my-2">
                        <input
                        type="text"
                        class="form-control shadow-none p-2"
                        placeholder="Subject"
                        />
                    </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-12">
                    <div class="form-group mx-3 my-2">
                        <textarea
                        class="form-control shadow-none p-2"
                        placeholder="Type Your Message Here"
                        cols="30"
                        rows="10"
                        ></textarea>
                    </div>
                    </div>
                </div>
                <div class="row">
                    <div class="my-2 col-md-12 justify-content-start">
                    <input
                        type="submit"
                        class="btn cbtn px-5 py-2"
                        style="
                        color: black;
                        background-color: rgb(235, 133, 16);
                        color: #fff;
                        "
                        value="Submit"
                    />
                    </div>
                </div>
                </form>
            </div>
            </div>
        </div>
        </section>

        <section id="map" class="my-5 py-4">
        <div class="container">
            <h1
            class="text-uppercase text-dark text-center mb-3 come"
            style="font-weight: bold"
            >
            come pay us a visit
            </h1>
            <div class="mapouter">
            <div class="gmap_canvas">
                <iframe
                width="100%"
                height="100%"
                id="gmap_canvas"
                src="https://maps.google.com/maps?q=45A,%20Alternative%20Route,%20Chevron%20Drive,%20Lekki,%20Lagos.&t=&z=13&ie=UTF8&iwloc=&output=embed"
                frameborder="0"
                scrolling="no"
                marginheight="0"
                marginwidth="0"
                ></iframe
                ><a href="https://2piratebay.org"></a><br /><a
                href="https://www.embedgooglemap.net"
                >how to insert google map into website</a
                >
            </div>
            </div>
        </div>
        </section>
    </div>
    </template>
        
        <script>
    export default {
    name: "Contact",
    };
    </script>
        
        <style lang="scss" scoped>
    .hhh::after {
    content: "";
    display: block;
    margin: 8px 0;
    height: 5px;
    width: 190px;
    background-color: rgb(235, 133, 16);
    }
    .maprouter {
    position: relative;
    text-align: right;
    height: 500px;
    width: 100% !important;
    }
    .gmap_canvas {
    overflow: hidden;
    background: none !important;
    height: 500px;
    width: 100% !important;
    }
    .come::after {
    content: "";
    display: block;
    margin: 10px auto;
    height: 5px;
    width: 50px;
    background-color: rgb(235, 133, 16);
    }
    #contact {
    width: 100%;
    background: linear-gradient(rgb(222, 139, 44), rgba(61, 60, 60, 0.7)),
        url(../assets/images/7.jpg);
    background-position: center;
    background-attachment: fixed;
    background-size: cover;
    //   height: 50vh;
    justify-content: center;
    flex-direction: column;
    display: flex;
    align-items: center;
    }
    </style>