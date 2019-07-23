<template>
    <div>

        
        <section class="section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-3 bg-gradient-default-local ">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pt-lg pb-10">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                        <h2 class="display-3 text-white">Choose your destination</h2>
                        <p class="lead text-white">In IEEE ANNU branch we are proud to have more than one online service that we offer to our community members and the masses, feel free to explore our services and share your thoughts on them  </p>
                    </div>
                </div>
                <div class="row row-grid row-eq-height mt-5">
                   
                    <div class="col-lg-4">
                        <card hover shadow class="shadow-lg--hover mt-5 " type="dark" >
                            <img class="card-img-top" src="/img/BranchCardBG.png"  height="400px" alt="Card image">
                            <div class="card-img-overlay">  
                                <div class="d-flex flex-column px-3">
                                    <div>
                                    <img src="/img/TLAP-LOGO.png" alt="IEEE ANNU logo" width="100%">
                                    </div>
                                    <div class="pl-4">
                                        <!-- <h5 class="title text-success">TLAP</h5> -->
                                        <p >Learn how programmers think and improve your logical thinking power and open new worlds for you</p>
                                        <div class="notice">
                                            <p class="text-warning">Under Maintenance</p>
                                        </div>
                                        <button type="button" onclick="location.href='http://www.ieee-annu.com/TLAP';" class="btn btn-outline-success">Learn more</button>
                                    </div>
                                </div>
                            </div>
                        </card>
                    </div>
                     <div class="col-lg-4">
                        <card shadow hover class="shadow-lg--hover mt-5" type="dark">
                            <img class="card-img-top" src="/img/BlackHoleCardBG.png"  height="400px" alt="Card image">
                            <div class="card-img-overlay">  
                                <div class="d-flex flex-column px-3">
                                    <div>
                                    <img src="/img/BlackHole-logo-white.png" alt="IEEE ANNU logo" width="100%">
                                    </div>
                                    <div class="pl-4">
                                        <!-- <h5 class="title text-success">BlackHole</h5> -->
                                        <p class="text-secondary">Scientafic and well written Arabic content in addition to well produced and compelling scientific videos .</p>
                                        <button type="button" onclick="location.href='http://www.ieee-annu.com/BlackHole';" class="btn btn-outline-success">Learn more</button>
                                    </div>
                                </div>
                            </div>

                        </card>
                    </div>
                    <div class="col-lg-4">
                        <card hover shadow bodyClasses="h-100" class="shadow-lg--hover mt-5">
                            <img class="card-img-top" src="/img/BranchCardBG.png"  height="400px" alt="Card image">
                            <div class="card-img-overlay">  
                                <div class="d-flex flex-column px-3">
                                    <div>
                                    <img src="/img/IEEE-ANNU-LOGO.png" alt="IEEE ANNU logo" width="100%">
                                    </div>
                                    <div class="pl-4">
                                        <!-- <h5 class="title text-success">Branch Site</h5> -->
                                        <p >Keep track of our achievements and last events and be the first one to reserve your spot in our next event. </p>
                                        <button type="button" onclick="location.href='http://branch.ieee-annu.com';" class="btn btn-outline-success">Learn more</button>
                                    </div>
                                </div>
                            </div>
                        </card>
                    </div>
                </div>
            </div>
        </section>
       
        <section >
            <div class="container">
                <div class="row row-grid justify-content-center">
                    <div class="col-lg-8 text-center">
                       
                        <div class="text-center">
                            <h4 class="display-4 mb-5 mt-5">Available Societies</h4>
                            <div class="row justify-content-center">
                                <div class="col-lg-2 col-4">
                                    <a href="#"  data-toggle="tooltip"
                                       data-original-title="Bootstrap 4 - Most popular front-end component library">
                                        <img v-lazy="'/img/WIE-logo.png'"
                                             class="img-fluid opacity-5">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="#"  data-toggle="tooltip"
                                       data-original-title="[Coming Soon] Sketch - Digital design toolkit">
                                        <img v-lazy="'/img/CS-logo.png'"
                                             class="img-fluid opacity-5">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="#" data-toggle="tooltip"
                                       data-original-title="[Coming Soon] Adobe Photoshop - Software for digital images manipulation">
                                        <img v-lazy="'/img/ComSoc-logo.png'"
                                             class="img-fluid  opacity-5">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="#"  data-toggle="tooltip"
                                       data-original-title="Vue.js - The progressive javascript framework">
                                        <img v-lazy="'/img/IAS-logo.png'"
                                             class="img-fluid opacity-5">
                                    </a>
                                </div>
                                <div class="col-lg-2 col-4">
                                    <a href="#"  data-toggle="tooltip"
                                       data-original-title="[Coming Soon] Angular - One framework. Mobile &amp; desktop">
                                        <img v-lazy="'/img/PES-logo.png'"
                                             class="img-fluid opacity-5">
                                    </a>
                                </div>
                               
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </div>
</template>

<script>
export default {
  name: "home",
  components: {}
};
</script>

<style>
.bg-BlackHole{
    background-image: url('/img/TLAP-LOGO.png')
}
.notice{
    position: absolute;
    bottom: 0;
    right: 5px;
}
.bg-gradient-default-local {
	background: linear-gradient(87deg, #225e9b 0, #4e7eaf 100%) !important;
}
</style>

