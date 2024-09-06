<template>
    <div class="intro-wrapper mb-4">
        <div class="swiper-container swiper-theme nav-inner swiper-nav-md animation-slider" data-swiper-options="{
                          'autoplay': {
                              'delay': 8000,
                              'disableOnInteraction': false
                          }
                      }">
            <div class="swiper-wrapper row cols-1 gutter-no">
                <div class="swiper-slide banner banner-fixed intro-slide intro-slide1 br-sm" style="background-image: url(assets/images/demos/demo3/slides/slide-1.jpg);
                              background-color: #262729;">
                    <div class="banner-content y-50 x-50 w-100 text-center">
                        <h5 class="banner-subtitle text-primary font-weight-normal text-capitalize font-secondary ls-25 slide-animate"
                            data-animation-options="{'name': 'fadeInDownShorter', 'duration': '.8s'}">Mega Sale
                        </h5>
                        <h3 class="banner-title text-white text-capitalize ls-25 lh-1 slide-animate"
                            data-animation-options="{'name': 'fadeInRightShorter', 'duration': '.5s', 'delay': '.5s'}">
                            2021 Men's Lifestyle</h3>
                        <p class="ls-25 slide-animate" data-animation-options="{
                                          'name': 'fadeInLeftShorter', 'duration': '.5s', 'delay': '.5s'
                                      }">Get Free Shipping on all orders over $99.00</p>
                        <a href="shop-banner-sidebar.html"
                           class="btn btn-white btn-outline btn-rounded btn-icon-right slide-animate"
                           data-animation-options="{'name': 'fadeInUpShorter', 'duration': '.5s', 'delay': '.5s'}">
                            Shop Now<i class="w-icon-long-arrow-right"></i>
                        </a>
                    </div>
                </div>
                <!-- End Of Intro Slide 1 -->
                <div class="swiper-slide banner banner-fixed intro-slide intro-slide2  br-sm" style="background-image: url(assets/images/demos/demo3/slides/slide-2.jpg);
                                  background-color: #DCE0DF;">
                    <div class="banner-content y-50">
                        <h5 class="banner-subtitle text-primary font-secondary font-weight-normal text-capitalize mb-0 lh-1 ls-25 slide-animate"
                            data-animation-options="{'name': 'fadeInDownShorter', 'duration': '.8s'}">Best
                            Seller</h5>
                        <h3 class="banner-title text-capitalize lh-.8 slide-animate"
                            data-animation-options="{'name': 'fadeInDownShorter', 'duration': '.8s', 'delay': '.4s'}">
                            Kitchen Electronic</h3>
                        <p class="text-default font-weight-normal ls-25 slide-animate" data-animation-options="{
                                          'name': 'fadeInDownShorter', 'duration': '.8s', 'delay': '.6s'
                                      }">Get Free Shipping on all orders over <strong class="text-primary">$99.00</strong>
                        </p>
                        <a href="shop-banner-sidebar.html"
                           class="btn btn-white btn-rounded btn-icon-right slide-animate"
                           data-animation-options="{'name': 'fadeInDownShorter', 'duration': '.8s', 'delay': '.8s'}">Shop
                            Now<i class="w-icon-long-arrow-right"></i></a>
                    </div>
                </div>
                <!-- End of Intro Slide 3 -->
                <div class="swiper-slide banner banner-fixed intro-slide intro-slide3 br-sm" style="background-image: url(assets/images/demos/demo3/slides/slide-3.jpg);
                                  background-color: #696A6E;">
                    <div class="banner-content y-50 text-right">
                        <div class="slide-animate" data-animation-options="{
                                          'name': 'fadeInUpShorter', 'duration': '.7s'
                                      }">
                            <h5
                                    class="banner-subtitle text-primary font-secondary font-weight-normal ls-25 mb-0 lh-1">
                                New Arrivals</h5>
                            <h3 class="banner-title text-white text-capitalize lh-1">Sports Sneakers</h3>
                            <p class="text-white ls-25">Get Free Shipping on all orders over
                                <strong>$99.00</strong></p>
                            <a href="shop-banner-sidebar.html"
                               class="btn btn-white btn-outline btn-rounded btn-icon-right">
                                Shop Now<i class="w-icon-long-arrow-right"></i></a>
                        </div>
                    </div>
                </div>
            </div>
            <button class="swiper-button-next"></button>
            <button class="swiper-button-prev"></button>
        </div>
    </div>
</template>

<script>
    export default {
        name: "IntroWrapper"
    }
</script>

<style scoped>

</style>