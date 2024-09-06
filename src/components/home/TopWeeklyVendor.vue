<template>
    <h2 class="title text-left appear-animate mb-5">Top Weekly Vendors</h2>
    <div class="swiper-container swiper-theme shadow-swiper  vendor-wrapper appear-animate mb-6" data-swiper-options="{
                      'spaceBetween': 20,
                      'slidesPerView': 1,
                      'breakpoints': {
                          '576': {
                              'slidesPerView': 2
                          },
                          '768': {
                              'slidesPerView': 3
                          },
                          '992': {
                              'slidesPerView': 4
                          }
                      }
                  }">
        <div class="swiper-wrapper row cols-xl-4 cols-md-3 cols-sm-2 cols-1">
            <div class="swiper-slide vendor-widget">
                <div class="vendor-widget-banner">
                    <figure class="vendor-banner">
                        <a href="vendor-dokan-store.html">
                            <img src="assets/images/demos/demo3/vendors/1.jpg" alt="Vendor Banner" width="1200"
                                 height="390" style="background-color: #ECE7DF;" />
                        </a>
                    </figure>
                    <div class="vendor-details">
                        <figure class="vendor-logo">
                            <a href="vendor-dokan-store.html">
                                <img src="assets/images/demos/demo3/vendors/brand-1.jpg" alt="Vendor Logo"
                                     width="90" height="90" />
                            </a>
                        </figure>
                        <div class="vendor-personal">
                            <h4 class="vendor-name">
                                <a href="vendor-dokan-store.html">OAIO Store</a>
                            </h4>
                            <span class="vendor-product-count">27 Products</span>
                        </div>
                    </div>
                </div>
                <!-- End of Vendor Widget Banner -->
            </div>
            <div class="swiper-slide vendor-widget">
                <div class="vendor-widget-banner">
                    <figure class="vendor-banner">
                        <a href="vendor-dokan-store.html">
                            <img src="assets/images/demos/demo3/vendors/2.jpg" alt="Vendor Banner" width="1200"
                                 height="390" style="background-color: #293936;" />
                        </a>
                    </figure>
                    <div class="vendor-details">
                        <figure class="vendor-logo">
                            <a href="vendor-dokan-store.html">
                                <img src="assets/images/demos/demo3/vendors/brand-2.jpg" alt="Vendor Logo"
                                     width="90" height="90" />
                            </a>
                        </figure>
                        <div class="vendor-personal">
                            <h4 class="vendor-name">
                                <a href="vendor-dokan-store.html">Trident Store</a>
                            </h4>
                            <span class="vendor-product-count">11 Products</span>
                        </div>
                    </div>
                </div>
                <!-- End of Vendor Widget Banner -->
            </div>
            <div class="swiper-slide vendor-widget">
                <div class="vendor-widget-banner">
                    <figure class="vendor-banner">
                        <a href="vendor-dokan-store.html">
                            <img src="assets/images/demos/demo3/vendors/3.jpg" alt="Vendor Banner" width="1200"
                                 height="390" style="background-color: #B8CDCE;" />
                        </a>
                    </figure>
                    <div class="vendor-details">
                        <figure class="vendor-logo">
                            <a href="vendor-dokan-store.html">
                                <img src="assets/images/demos/demo3/vendors/brand-3.jpg" alt="Vendor Logo"
                                     width="90" height="90" />
                            </a>
                        </figure>
                        <div class="vendor-personal">
                            <h4 class="vendor-name">
                                <a href="vendor-dokan-store.html">Pam Store</a>
                            </h4>
                            <span class="vendor-product-count">16 Products</span>
                        </div>
                    </div>
                </div>
                <!-- End of Vendor Widget Banner -->
            </div>
            <div class="swiper-slide vendor-widget">
                <div class="vendor-widget-banner">
                    <figure class="vendor-banner">
                        <a href="vendor-dokan-store.html">
                            <img src="assets/images/demos/demo3/vendors/4.jpg" alt="Vendor Banner" width="1200"
                                 height="390" style="background-color: #F5F5F5;" />
                        </a>
                    </figure>
                    <div class="vendor-details">
                        <figure class="vendor-logo">
                            <a href="vendor-dokan-store.html">
                                <img src="assets/images/demos/demo3/vendors/brand-4.jpg" alt="Vendor Logo"
                                     width="90" height="90" />
                            </a>
                        </figure>
                        <div class="vendor-personal">
                            <h4 class="vendor-name">
                                <a href="vendor-dokan-store.html">K Group Store</a>
                            </h4>
                            <span class="vendor-product-count">25 Products</span>
                        </div>
                    </div>
                </div>
                <!-- End of Vendor Widget Banner -->
            </div>
        </div>
        <div class="swiper-pagination"></div>
    </div>
</template>

<script>
    export default {
        name: "TopWeeklyVendor"
    }
</script>

<style scoped>

</style>